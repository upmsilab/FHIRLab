# Problem Statement

Welcome to **Utopia**, a fictional country working to improve its digital health response following a recent infectious disease outbreak.

The existing paper intake form has led to **inconsistent and unstructured data collection** across facilities, making it difficult to aggregate, analyse, and respond effectively at the national level. Critical information is often **missing, misinterpreted, or delayed**, especially when shared between systems or regions.

As part of the Ministry of Health’s Clinical Informatics Group, your team has been tasked with transforming a **paper-based clinical intake form** into an electronic form that supports better data capture, sharing, and analysis during health emergencies.

To facilitate this, the Utopia Ministry of Health has also established a **national terminology server** to support the consistent use of clinical terminologies. This server includes access to the **SNOMED CT IPS Value Sets** and other national value sets to enable **semantic interoperability** across the health system.

## Your goal is to develop a standards-based electronic form that is:

- Machine-readable  
- Interoperable  
- Ready to be reused across facilities and systems  

You will use **FHIR** to model the form and ensure answers are coded using internationally recognised terminologies, such as **SNOMED CT** and **LOINC**, where applicable.

---

## Your Task

Each table represents a **clinical intformatics team**. Working together:

- Working together at each table, review the provided paper form (5 min). 
- Map questions to a corresponding FHIR Questionnaire item using the AidBox Form builder Chose the correct item type e.g., string, choice, date, Boolean etc. (15 min).
- Review and identify value sets for each form fields where answer could be a discrete list or predefined options e.g., Yes/No, Gender, Problems history. List of available value sets is provided (15 min). 
- Discuss your work among the group (5 min). 
- Download a sample FHIR Questionnaire JSON file to review: https://tinyurl.com/274kd7nn

 **Note:** If you don't have access to laptop, continue with the provided mapping sheet:

- **Form Field Name** (already printed)  
- **FHIR Questionnaire Type**  
- **Answer Value Set** from the **SNOMED CT  IPS Set** (if applicable)  

📎 Use the *Supporting Information* below for guidance on FHIR types and sample value sets.

---
## Supporting Resources for Prototyping

- AidBox FHIR Questionnaire Builder: https://form-builder.aidbox.app/
- FHIRLab Terminology Server End-Point: https://tx.fhirlab.net/fhir
- SNOMED CT ValueSets Provided by MOH Utopia
- Provided paper sheet for mapping and design thinking
- Instructions and FHIR Questionnaire item types provided at each table. 

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

### SNOMED CT IPS Value Sets provided by MOH Utopia

| ValueSet Name                          | URL                                                                                  |
|----------------------------------------|---------------------------------------------------------------------------------------|
| Allergy Intolerance – IPS (2.0.0)      | http://hl7.org/fhir/uv/ips/ValueSet/allergy-intolerance-uv-ips                      |
| Medications – IPS (2.0.0)              | http://hl7.org/fhir/uv/ips/ValueSet/medication-uv-ips                                |
| Problems – IPS (2.0.0)                 | http://hl7.org/fhir/uv/ips/ValueSet/problems-uv-ips|2.0.0                            |
| Vaccines – IPS (2.0.0)                 | http://hl7.org/fhir/uv/ips/ValueSet/vaccines-uv-ips|2.0.0                            |
| Results Radiology Observation – IPS    | http://hl7.org/fhir/uv/ips/ValueSet/results-radiology-observations-uv-ips           |
| Vaccine Target Diseases – IPS (2.0.0)  | http://hl7.org/fhir/uv/ips/ValueSet/target-diseases-uv-ips                           |
| Problem Type – IPS (2.0.0)             | http://hl7.org/fhir/uv/ips/ValueSet/problem-type-uv-ips                              |
| Allergy Reaction – IPS (2.0.0)         | http://hl7.org/fhir/uv/ips/ValueSet/allergy-reaction-uv-ips|2.0.0                    |


### Example National Value Sets

- Sex | https://tx.fhirlab.net/fhir/ValueSet/utopia-sex-birth
- Region Codes | urn://example.com/ph-core/fhir/ValueSet/regions|0.1.0

---

**Note:** If you are working on a computer, download the [JSON Questionnaire](./utopia-health-intake-form.json) to get started.
