---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Medical Terminology
description: A Gentle Introduction to FHIR Terminology

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
        content: Codeable Concept
        external_url: true
        url: 'https://hl7.org/fhir/R5/datatypes.html#CodeableConcept'
    next:
        content: Terminology Server
        url: '../services/Ontoserver'
        external_url: false

# gemini prompt: provide a gentle introduction to FHIR terminilogy for medically trained staff. Begin with the idea of a codeable concept. Use questionnaires as a use case.

---

# Codeable Concepts

At the heart of FHIR terminology is a resource type called the *codeable concept*. This is a fundamental building block used to represent medical terms and concepts in a standardized way. A codeable concept is essentially a medical term, such as "diabetes mellitus," along with a code that uniquely identifies it within a specific code system.

# Why Concepts Matter

Imagine a world where every healthcare provider and system uses the same language to describe medical conditions, treatments, and procedures. This is the goal of codeable concepts. By using standardized codes, we can ensure that data is shared accurately and efficiently across different systems, leading to improved patient care.

# Example: Questionnaires

Let's consider a simple questionnaire designed to assess a patient's risk for heart disease. The questionnaire might include questions like:

1. **Do you have a family history of heart disease?**
2. **What is your blood pressure?**
3. **What is your cholesterol level?**
4. **Do you smoke?**

To represent these questions in FHIR, we would use codeable concepts. For example:

* **"Family history of heart disease"** could be represented by a code from the [SNOMED CT code system](https://en.wikipedia.org/wiki/SNOMED_CT).
* **"Blood pressure"** and **"cholesterol level"** could be represented by [codes from LOINC](https://en.wikipedia.org/wiki/LOINC).
* **"Smoking"** could be represented by a code from a specific smoking status [code system](https://www.hl7.org/fhir/codesystem.html).

By using codeable concepts, we can ensure that the questionnaire is understood and interpreted consistently across different healthcare systems. This is crucial for data analysis, research, and clinical decision-making.

# The Benefits

* **Improved Data Quality:** Consistent use of codeable concepts reduces errors and inconsistencies in data entry.
* **Enhanced Interoperability:** Standardized terminology allows for seamless data exchange between different systems.
* **Accelerated Research:** By using standardized data, researchers can more easily analyze large datasets and discover new insights.
* **Better Patient Care:** Accurate and consistent data leads to more informed clinical decisions and improved patient outcomes.

By understanding the basics of codeable concepts and FHIR terminology, you can contribute to a future where healthcare data is shared efficiently and effectively, ultimately benefiting patients and providers alike.

# Learn more!

Follow the Yellow Brick Code by 

* either [Reading it](https://www.devdays.com/wp-content/uploads/2023/08/230606_DionMcMurtrie_Yellow-Brick-Code.pdf),
* or [Watching it](https://youtu.be/40Lvv2t8OxU?si=m20daFNMDSD7TBab).

 
