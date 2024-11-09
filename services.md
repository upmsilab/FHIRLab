---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Services
description: "FHIRLab - What is in the sandbox"

# Author box
# author:
#    title: "by Google Gemini"
#    title_url: 'https://en.wikipedia.org/wiki/Gemini_(language_model)'
#    external_url: true
#    description: "content created by LLM"

# Micro navigation
micro_nav: true

# Page navigation
# page_nav:
#   prev:
#        content: Community
#        url: '../community'
#    next:
#        content: Vision
#        url: '../vision'


# Grid navigation
grid_navigation:
    - title: HAPI
      excerpt: Our Clinical Data Repository (CDR).
      cta: Work with medical data ...
      url: '#'
    - title: Ontoserver
      excerpt: Our Terminology Server (TX).
      cta: Work with medical terminology ...
      url: '#'

---
<div class="callout callout--danger">
<strong>The sandbox is not intended for production use. Please don't store any real PHI Data</strong>

<p>The sandbox is intended for non-production development, testing and validation use only. Do not store real patient health information or any identifiable data.</p>

<strong>Only use synthetic data for testing, validation and learning.</strong>

</div>

# FHIR Server

   HAPI FHIR server with open access.

   Software | HAPI FHIR R4 Server
   FHIR Base URL | [https://cdr.fhirlab.net/fhir]([https://cdr.fhirlab.net/fhir])
   

# Terminology Server

   CSIRO [Ontoserver](Ontoserver) is used as shared terminology across the platform

   Software | CSIRO Ontoserver
   FHIR Version | 4.0.1
   Supported Formats | application/fhir+xml, xml, application/fhir+json, json
   FHIR Endpoint | [https://tx.fhirlab.net/fhir](https://tx.fhirlab.net/fhir)
    

# Validator

   HL7  Validator for FHIR Resource Validation

   HL7 Validator | [https://validator.fhirlab.net/](https://validator.fhirlab.net/)


<div class="callout callout--info">
<strong>Watch this space as we grow our environment</strong>

<p>CSIRO SSCP and UPM SILab are collaboration with regional stakeholders and technology partners to grow the application footprint and include some simulated point-of-care systems such as, Bahmni, OPEN MRS, SMILE CDR.</p> 

</div>
