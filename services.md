---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Services
description: "FHIRLab - What is in the sandbox"

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
        content: Community
        url: '../community'
    next:
        content: Vision
        url: '../vision'

# gemini prompt: provide an introduction to FHIR terminology for staff in software engineering and information technology. Focus on savings of integration and ease of deployment. Offer links to standards and example instances of servers.


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

Welcome. Glad we can be of service. Before you begin, please take in and heed the warning below. It is important and a condition of entry to FHIRLab's services.


<div class="callout callout--danger">
<strong>Warning: Do Not Store Real Patient Information</strong>

<p>This FHIR Sandbox is for testing and development purposes only. Do not store any real patient information on Sandbox servers. Storing real patient data on a public or unsecured server poses significant privacy and security risks.</p>

<strong>Only use synthetic or anonymized data for all activities.</strong>

</div>

Otherwise, you may want to look at our [Core Components](#core-components), the surrounding [Peripherals]() and how to [keep up-to-date]() with what is happening.

# Core Components

The core components form the basic FHIR learning sandbox which includes the components below. Click to have a look.

| Role                     | Project       | Entry Point      |
|--------------------------|---------------|------------------------------|
| [Clinical Data Repository](#clinical-data-repository) | [HAPI](HAPI)          | [http://cdr.fhirlab.net](http://cdr.fhirlab.net)       |
| [Terminology Server](#terminology-server)       | [Ontoserver](Ontoserver)    | [http://tx.fhirlab.net](http://tx.fhirlab.net)        |
| [Validator](#validator)                | [HL7 Validator](Validator) | [http://validator.fhirlab.net](http://validator.fhirlab.net) |
| [Testing Tool](#testing-tool)             | [Inferno](Inferno)       | [http://inferno.fhirlab.net](http://inferno.fhirlab.net)   |

These components provide a foundation for learning and experimenting with FHIR, enabling you to create and test FHIR-based applications. They form a set of essential open source FHIR components that together form a reference for a learner and are fairly easily replicated for local experimentation.

Please find details on our selected components and their roles below:

## Clinical Data Repository

   FHIRLab's CDR is the [HAPI Server](HAPI).
   
   * A centralized repository of standardized health data. 
   * Stores patient records, lab results, medications, and other relevant clinical information.
   * Enables data-driven insights and supports clinical decision-making.

## Terminology Server

   FHIRLab's Terminology Server is the [Ontoserver](Ontoserver).

   * Provides a central source of standardized healthcare terminology.
   * Includes code systems, value sets, and concept maps.
   * Ensures consistent data representation and interoperability.   

## Validator

   FHIRLab's Validator is the [HL7 Validator](Validator).

   * Verifies the accuracy and completeness of FHIR resources.
   * Checks compliance with FHIR standards and local implementation guidelines.
   * Helps developers identify and correct errors in their FHIR implementations.   

## Testing Tool

   FHIRLab's Testing Tool is [Inferno](Inferno).

   * Offers a range of tools for testing FHIR-based applications.
   * Includes test data generators, performance testing tools, and security testing tools.
   * Facilitates the development of robust and secure FHIR solutions.

# Peripheral Components

The Peripheral Components, also known as the **Galaxy** are a dynamic learning environment designed to provide hands-on experience with cutting-edge FHIR-enabled healthcare solutions. This cluster will bring together a curated collection of industry-leading applications, and may ultimately include [Bahmni](https://www.bahmni.org/), [OpenMRS](https://openmrs.org/), and [SMILE CDR](https://www.smiledigitalhealth.com/), to offer learners a comprehensive understanding of real-world healthcare IT systems.


By interacting with these applications within the Galaxy environment, learners can:

* **Explore FHIR Interoperability:** Gain practical insights into how FHIR enables seamless data exchange between different healthcare systems.
* **Experiment with Clinical Workflows:** Simulate real-world clinical scenarios and test various approaches to patient care.
* **Develop Custom Solutions:** Build custom FHIR-based applications and integrations.
* **Collaborate with Peers:** Connect with other learners and share knowledge and experiences.

The Galaxy provides a safe and controlled environment to learn and experiment, empowering the next generation of healthcare IT professionals to drive innovation and improve patient care. 

# Service Updates

<div class="callout callout--info">
<strong>Watch this space as we grow our environment</strong>

<p>FHIRLab is constantly improving and growing. To keep up-to-date on new offerings and changes, you can subscribe to our <a href="https://en.wikipedia.org/wiki/Atom_(web_standard)">ATOM feed</a>.</p> 

<strong>FHIRLabs service update atom feed is here: <a href="../../feed.xml">feed.xml</a>.</strong>

</div>
