---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Ontoserver
description: "a leading FHIR terminology server"

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
        content: Validator
        url: '../Validator'

# gemini prompt: Provide an introduction to FHIR terminology for university students. Focus on the prospect of improving people's lives through the implementation of this technology. Add a call to action for learning.

---

Ontoserver is a leading FHIR terminology server that provides efficient and reliable access to clinical terminologies. It is designed to simplify the use of complex terminologies like SNOMED CT by addressing key challenges faced by implementers.

Its documentation is located at [https://ontoserver.csiro.au/site/technical-documentation/](https://ontoserver.csiro.au/site/technical-documentation/).

# User Interfaces

* The main browser-based user interface of our server is located here: [https://tx.fhirlab.net/](https://tx.fhirlab.net/)
* This interface is [OntoCommand](https://ontoserver.csiro.au/site/technical-documentation/ontocommand-documentation/), a [Progressive Web App (PWA)](https://en.wikipedia.org/wiki/Progressive_web_app) whose code is hosted by CSIRO. This design means that no data is sent to CSIRO at all. All communication is between your browser and FHIRLab.
* The OntoCommand interface also provides access to the included CSIRO terminology management applications [Shrimp](https://ontoserver.csiro.au/site/our-solutions/shrimp/) and [Snapper](https://ontoserver.csiro.au/site/technical-documentation/snapper-documentation/).

# Key Features

* **FHIR-Native:** Ontoserver fully implements the FHIR terminology services API, allowing seamless integration with FHIR-based applications.
* **Deep SNOMED CT and LOINC Features:** It offers extensive support for SNOMED CT and LOINC, including advanced search capabilities and semantic reasoning.
* **SNOMED CT Expression Constraint Language (ECL):** Ontoserver supports ECL, a powerful language for defining complex queries and constraints on SNOMED CT concepts.
* **Multiple SNOMED CT Versions:** It can manage and query multiple versions of SNOMED CT, ensuring compatibility with different systems and standards.
* **OWL2 EL (with Concrete Domains) Description Logic:** Ontoserver utilizes OWL2 EL reasoning to provide accurate and efficient semantic reasoning over terminology data.
* **Syndication:** Ontoserver supports syndication, allowing it to receive updates from upstream sources like the National Clinical Terminology Service (NCTS) and distribute them to other Ontoserver instances.

# Benefits

* **Improved Data Quality:** Ensures consistent and accurate use of clinical terminologies.
* **Enhanced Interoperability:** Facilitates seamless data exchange between different healthcare systems.
* **Accelerated Development:** Provides a robust and efficient platform for building FHIR-based applications.
* **Reduced Costs:** Streamlines the process of managing and maintaining clinical terminologies.

By leveraging Ontoserver, healthcare organizations can improve the quality and efficiency of their clinical systems, ultimately leading to better patient care.
