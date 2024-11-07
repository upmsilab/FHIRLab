---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: "Validator"
description: "checks the validity of FHIR resources"

# Author box
author:
    title: "by Google Gemini"
    title_url: 'https://en.wikipedia.org/wiki/Gemini_(language_model)'
    external_url: true
    description: "content created by LLM"

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: HAPI
        url: '../HAPI'
    next:
        content: Inferno
        url: '../Inferno'

# gemini prompt: describe the HL7 FHIR validator web application

---

HL7 provides a web-based FHIR validatör that allows users to validate FHIR resources against the FHIR specification and Implementation Guides (IGs). This tool is essential for ensuring the accuracy and interoperability of FHIR-based systems.

The documentation for the validator is located at [https://confluence.hl7.org/display/FHIR/Using+the+FHIR+Validator](https://confluence.hl7.org/display/FHIR/Using+the+FHIR+Validator). The user interface has equivalent settings to all command-line options. The main flow of actions is described below.

# User Interface and Flow

1. **Access the Validator:** Visit the [FHIRLab Validator website](https://validator.fhirlab.net).
2. **Upload Resource:** Select the FHIR resource file you want to validate and upload it to the validator.
3. **Choose Validation Options:** Select the appropriate FHIR version and any relevant IGs.
4. **Validate:** Click the "Validate" button to initiate the validation process.
5. **Review Results:** The validator will display the validation results, including any errors or warnings.

# Key Features

* **Resource Validation:** Users can upload FHIR resources in various formats (JSON, XML, etc.) and validate them against the specified FHIR version and IG.
* **Error Reporting:** The validator provides detailed error messages and explanations for any validation failures, helping users identify and correct issues.
* **IG Support:** The validator can be configured to validate against specific IGs, ensuring compliance with custom requirements.
* **User-Friendly Interface:** The web interface is designed to be intuitive and easy to use, making it accessible to a wide range of users.

By using the HL7 FHIR Validator, you can ensure that your FHIR resources are well-formed, compliant with the standard, and interoperable with other systems.
