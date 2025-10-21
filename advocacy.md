---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Advocacy
description: "FHIRLab is designed to support advocacy efforts for the adoption of health data interoperability and standards including but not limited to HL7 FHIR, SNOMED CT, and LOINC. It allows stakeholders and policy makers to experience the real-world value of interoperability through hands-on activities, use cases, walkthroughs all using standards-based digital health tools."

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Learning
        url: '#'
    next:
        content: Testing
        url: '/services'

---

**Accelerating the adoption of digital health, standards and interoperability**
The Sandbox offers a simulated functional environment to demystify digital health interoperability and enables decision-makers and implementers to see how interoperability improves patient care, health system performance, and data-driven decision-making through real-world healthcare use cases and interactive walkthroughs. 

# Who can use the sandbox for Advocacy?
- Policymakers and Health System Leaders
- Healthcare Workers
- Health IT Implementers and Developers
- Educators and Trainers in Digital Health
- Development Partners and Donors

# Use Cases
FHIRLab resoures make it easy to explore and understand the practical applications of Digital Health Standards and Interoperability. You can explore the tools and setup your own workflows to support adoptions. 

For starting, we have also curated some examples of how different actors can use the tools currently available in the sandbox.

## Understand foundational cocnepts for standards
Learn foundational concepts of FHIR, and terminology, and why they matter.

### Terminology Services 
See basic terminology concepts in actions, with mappings and codesystem usage (e.g. SNOMED, LOINC) OR Create your own ValueSets for demonstration. 

1. Open [FHIRLab Ontoserver](https://tx.fhirlab.net/) no username/password required
2. Explore generic Codesystems, ValueSets and Concepts using Shrimp tool. Trying finding your favorutive SNOMED or LOINC concepts. 
3. Open snapper tool and try to (create a new codesystem, add Valuesets and Concepts)[https://ontoserver-wp.csiro.au/technical-documentation/snapper-documentation/snapperauthor-guide/add-a-new-fhir-resource/create-a-new-codesystem/].
5. Use [postman](https://www.postman.com/downloads/) or any other API testing tool to try simple activities such as, finding a concept or expanding a valueset.
6. You can also use [example postman collections](https://www.postman.com/jimsteel/ontoserver/collection/k4gv6q6/ontoserver-6-example-fhir-terminology-requests) to help you get started. Please use FHIRLab Ontoserver API endpoint as URL i.e. https://fhirlab.net/fhir/

### FHIR Resources
Learn about FHIR reources and explore basic resources using HAPI FHIR Server and understand how data is represented in FHIR OR Create your first FHIR resource using HAPU UI or Postman.
 
1. Open FHIR Server for UI: https://cdr.fhirlab.net OR use the FHIR API endpoint in postman: https://cdr.fhirlab.net/fhir - no authentication required
2. Explore existing FHIR resource by querying the server and understand how FHIR is structured
3. Try adding a new resource into the server. Don't worry FHIRLab is design for you to break it.

If you need help to get started, try example [postman collections](https://github.com/upmsilab/2025JuneFHIRConnectathon?tab=readme-ov-file#sample-postman-collections-and-data) from our recent FHIR Connectathon to kick-off

## Demonstrating Standards in Action
Showcase standards in action using real world healthcare examples through synthetic patient data.

### FHIR Questionnaire and Forms
Explore the basic use of FHIR questinnaires and convert paper forms into standardised FHIR questionnaires for Data Capturing and Exchange across multiple application. A single standardised form can be used across different EMRs and Modile applications for data capturing. This help standardise the input and improve data quality. 

We will use Aidbox FHIR Platform available in the FHIRLab to support this learning activity. You can also use other standards-based tools such as NLM forms for training and practice. 

1. Please request access to FHIRLab Aidbox instance (access is free for FHIRLab users). 
2. Login to AidBox and navigate to forms.
3. Upload any paper forms and convert it into FHIR Questionnaire using AI OR or do it manually

Use this [tutorial to get familair with aidbox forms modules](https://youtu.be/20bprWplCDo?si=J4xvTymjAWG2E0UC)

5. You can use any FHIR ValueSet into the form fields for coded data. 

**FHIRLab Resources**:
- **Bahmni/OpenMRS**: Explore pre-designed clinical workflows to understand how standardised structure data can be captured close to the point of care using terminologies and synthetic patient data.
- **Ontoserver**: Understand terminology concepts, mappings and standard code usage (e.g. SNOMED, LOINC).
- **OpenMRS Integration**: Explore how data Value Sets from a FHIR Terminology Server can be Integrated into a local EMR as interface terminology.

# Current Tools Available in FHIRLab

| Tool          | Description |
|---------------|-------------|
| **HAPI FHIR Server** | Open-source FHIR R4 server to store and query clinical data. |
| **Ontoserver** | FHIR Terminology server with support for SNOMED CT, LOINC, and custom value sets. |
| **(Coming Soon) OpenMRS** | Integrated EMR environment to simulate structured data capture and transformation into FHIR. |

---

Let's make interoperability real, together.
