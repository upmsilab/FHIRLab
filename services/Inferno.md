---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Inferno
description: "a powerful open-source framework for creating, executing, and sharing conformance tests for FHIR APIs"

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

Inferno is a powerful open-source framework for creating, executing, and sharing conformance tests for FHIR APIs. It's a valuable tool for ensuring that FHIR-based systems adhere to the standard and function as expected.

Its documentation is located at [https://inferno-framework.github.io/](https://inferno-framework.github.io/).

# User Interface

The browser-based user interfaces of our Inferno server is the [Suite selection page](https://inferno.fhirlab.net/). It allows to pick the built-in suite of tests and run it against the selected end-point. The current suites are examples taken from the Australian development context. Philipines-specific test kits have to be developed and installed.

# Key Features

* **Test Kit Creation:** Inferno provides a flexible framework for creating test kits, which are packages of tests designed to verify specific FHIR capabilities. These test kits can be tailored to different FHIR Implementation Guides (IGs) and use cases.
* **Test Execution:** Inferno can execute tests against FHIR servers, either locally or remotely, to assess their conformance to the FHIR standard and relevant IGs.
* **Test Reporting:** The framework generates detailed reports on test results, including pass/fail status, error messages, and performance metrics.
* **Community-Driven Development:** Inferno benefits from an active community of developers who contribute to its ongoing development and maintenance.
* **Integration with Other Tools:** Inferno can be integrated with other tools and frameworks, such as Jenkins and CI/CD pipelines, to automate testing and deployment processes.

# Workflow

1. **Test Kit Creation:** Developers create test kits using Inferno's DSL (Domain-Specific Language) or by extending existing test kits.
2. **Test Execution:** The test kit is executed against a FHIR server, sending requests and validating responses.
3. **Test Reporting:** Inferno generates detailed reports on the test results, highlighting any issues or failures.

# Benefits

* **Ensures FHIR Conformance:** By testing against a wide range of scenarios, Inferno helps ensure that FHIR-based systems adhere to the standard.
* **Improves Interoperability:** By promoting consistent implementation, Inferno helps to improve interoperability between different healthcare systems.
* **Accelerates Development:** By providing a standardized testing framework, Inferno helps developers to speed up the development and deployment of FHIR-based applications.
* **Identifies Issues Early:** By testing early and often, Inferno helps to identify and fix issues before they impact production systems.

Overall, Inferno is a valuable tool for anyone involved in developing or implementing FHIR-based systems. By using Inferno, you can ensure that your systems are reliable, interoperable, and compliant with the FHIR standard.