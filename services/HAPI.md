---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: HAPI Server
description: "HAPI: A Java FHIR Library and Server"

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
        content: Validator
        url: '../Validator'
    next:
        content: Ontoserver
        url: '../Ontoserver'

# gemini prompt: Provide an introduction to FHIR terminology for university students. Focus on the prospect of improving people's lives through the implementation of this technology. Add a call to action for learning.

---

HAPI FHIR is a popular open-source Java-based implementation of the HL7 FHIR standard. It provides a comprehensive framework for building FHIR-compliant servers and clients, enabling seamless interoperability between healthcare systems.

Its documentation is located at [https://hapifhir.io/hapi-fhir/docs/](https://hapifhir.io/hapi-fhir/docs/).

# User Interface

These are the browser-based user interfaces of our server:

* [Web Test Page](https://cdr.fhirlab.net/)
* [Swagger Page](https://cdr.fhirlab.net/fhir)

## HAPI Interface Philosophy

HAPI FHIR doesn't have a traditional web user interface like a web application with forms and buttons. Instead, it primarily exposes a RESTful API that can be interacted with using various tools and programming languages.

However, HAPI FHIR does provide a few web-based tools to help developers and administrators:   

## Web Test Page

The [Web Test Page](https://cdr.fhirlab.net/) is a simple web page that allows you to manually test your FHIR server by sending HTTP requests directly to it.   
It provides a basic interface to input FHIR resources in JSON or XML format and send them to the server.

## Swagger UI Integration
HAPI FHIR integrates with Swagger UI, a popular tool for visualizing and interacting with APIs. When you access the base URL of your HAPI FHIR server, you'll be automatically redirected to the [Swagger UI interface](https://cdr.fhirlab.net/fhir).

The Swagger UI provides a user-friendly interface to explore the HAPI FHIR API:

* API Documentation: You can view detailed documentation for each API endpoint, including request parameters, response formats, and error codes.
* Interactive API Console: You can directly test API endpoints by inputting request parameters and executing the requests.
* Code Generation: You can generate client code in various programming languages (e.g., Java, Python, JavaScript) to interact with the API.

## Purpose of the Web interfaces

The primary interaction with a HAPI FHIR server is through its RESTful API.
The web interfaces are supplementary tools to aid in development and administration.
By understanding the purpose of these web interfaces and leveraging the powerful RESTful API, you can effectively utilize HAPI FHIR to build robust and interoperable healthcare solutions.

# **Key Features**

* **Robust Server Implementation:** HAPI FHIR offers a robust server implementation that can handle a wide range of FHIR operations, including:
    * **Create, Read, Update, and Delete (CRUD) operations:** Perform basic data management tasks on FHIR resources.
    * **Search and Query:** Retrieve specific resources based on various criteria.
    * **Transaction and Batch:** Execute multiple operations in a single request.
    * **History:** Access the history of changes to a resource.
* **Flexible Client Library:** The HAPI FHIR client library allows you to interact with FHIR servers programmatically. It provides a simple API for sending requests and parsing responses.
* **Extensibility:** HAPI FHIR is highly customizable, allowing you to extend its functionality with custom resource types, validation rules, and security mechanisms.
* **Performance and Scalability:** HAPI FHIR is designed to handle high-volume workloads and can be scaled to meet the needs of large-scale healthcare systems.
* **Community Support:** A large and active community provides support, documentation, and contributions to the HAPI FHIR project.

# **Use Cases**

* **Building FHIR-based Applications:** Develop custom healthcare applications that can interact with FHIR servers.
* **Integrating Healthcare Systems:** Connect different healthcare systems, such as EHRs, laboratory systems, and imaging systems.
* **Data Exchange:** Facilitate the exchange of patient data between healthcare providers.
* **Research and Analytics:** Analyze large amounts of healthcare data to gain valuable insights.
* **Personal Health Records:** Empower individuals to manage their own health information.

**HAPI FHIR is a powerful tool for building interoperable healthcare solutions. By leveraging its features and capabilities, you can contribute to the advancement of healthcare and improve patient outcomes.**
