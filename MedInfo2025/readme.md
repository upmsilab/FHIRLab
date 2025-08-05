# Problem Statement

Welcome to **Utopia**, a fictional country working to improve its digital health response following a recent infectious disease outbreak.

As part of the Ministry of Health’s Clinical Design Group, your team has been tasked with transforming a **paper-based clinical intake form** into a digital version that supports better data capture, sharing, and analysis during health emergencies.

The existing paper form has led to **inconsistent and unstructured data collection** across facilities, making it difficult to aggregate, analyse, and respond effectively at the national level. Critical information is often **missing, misinterpreted, or delayed**, especially when shared between systems or regions.

To address this, the Utopia Ministry of Health has established a **national terminology server** to support the consistent use of clinical terminologies. This server includes access to the **SNOMED CT FREE IPS subset** and other standard value sets to enable **semantic interoperability** across the health system.

Your goal is to develop a **standards-based digital tool (form)** that is:

- Machine-readable  
- Interoperable  
- Ready to be reused across facilities and systems  

You will use **FHIR** to model the form and ensure answers are coded using internationally recognised terminologies, such as **SNOMED CT** and **LOINC**, where applicable.

---

# Your Task

Each table represents a **clinical design team**. Working together:

- Review the paper form provided  
- Map each field to a corresponding **FHIR Questionnaire item**, choosing the correct type (e.g., `string`, `choice`, `date`, `boolean`)  
- Identify value sets for fields with predefined answer options (e.g., Yes/No, Gender, list of problems)  

Then complete the provided mapping sheet with:

- **Form Field Name** (already printed)  
- **FHIR Questionnaire Type**  
- **Answer Value Set** from the **SNOMED CT Free IPS Set** (if applicable)  

📎 Use the *Supporting Information Sheet* below for guidance on FHIR types and sample value sets.

---

## Supporting Information Sheet

### FHIR Questionnaire Item Types

| Type         | Description                                                |
|--------------|------------------------------------------------------------|
| `string`     | Short free-text entry                                      |
| `date`       | Date (no time component)                                   |
| `boolean`    | Yes/No answer                                              |
| `choice`     | Single-coded answer from a predefined set                  |
| `text`       | Longer free-text paragraph                                 |
| `open-choice`| Single-coded answer from a predefined set with auto-suggest|

---

### SNOMED CT IPS Value Sets

- Allergy Intolerance – IPS (2.0.0)  
- Medications – IPS (2.0.0)  
- Problems – IPS (2.0.0)  
- Vaccines – IPS (2.0.0)  
- Results Radiology Observation – IPS (2.0.0)  
- Vaccine Target Diseases – IPS (2.0.0)  
- Problem Type – IPS (2.0.0)  
- Allergy Reaction – IPS (2.0.0)  

---

### National Value Sets

- Sex  
- Region Codes  

---

## Supporting Resources

- 🔗 [FHIRLab Sandbox Test Terminology Server](https://tx.fhirlab.net/fhir)  
- 🔗 [AidBox Public Form Builder](https://form-builder.aidbox.app/)  

---

**Note:** If you are working on a computer, download the [JSON Questionnaire](./MedInfo2025/utopia-health-intake-form.json) to get started.
