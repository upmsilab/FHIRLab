---
# Page settings
layout: default
keywords: FHIRFLARE, Implementation Guide, Toolkit, Validation, FHIR Resources
comments: false

# Hero section
title: FHIRFLARE Validation Guide
description: "A browser-based toolkit for validating FHIR resources against Implementation Guides"

# Author box
# author:
#    title: "Author Name"
#    title_url: 'author-profile-url'
#    external_url: true
#    description: "Author description"

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Services
        url: '../services'
    next:
        content: FHIRFLARE FSH Converter
        url: '../FHIRFLARE_FSH_Guide'

---

# FHIRFLARE Validation Toolkit – Quick Start Guide

**Hosted at:** [https://flare.fhirlab.net](https://flare.fhirlab.net)  
**Audience:** Medical personnel with basic understanding of FHIR and Implementation Guides (IGs)

## 1. Accessing the Toolkit

- Open your browser and go to: [https://flare.fhirlab.net](https://flare.fhirlab.net)
- No installation required — Lite Mode runs entirely in the browser.
- All validation and conversion operations are performed client-side or via lightweight server calls.

## 2. Selecting and Importing IGs from the FHIR Registry

### Steps

1. Navigate to **Search and Import IGs**.
2. Enter the IG name (e.g., `hl7.fhir.au.base`) and select the desired version.
3. Click **Import**.
4. The IG and its dependencies will be cached locally for validation use.

> IGs are sourced from the official FHIR registry and Simplifier.net.

## 3. Uploading a Local IG

### Steps

1. Package your Implementation Guide as a `.tgz` file.
   - **Note on naming convention**: Package filenames must follow FHIR package naming standards (which are based on [npm package naming](https://docs.npmjs.com/cli/v9/configuring-npm/package-json#name)):
   - Format: `publisher.category.name-version.tgz`
   - Example: `example.fhir.ph.core.r4-0.1.0.tgz`
   - The name must match the `name` and `version` fields in the package's `package.json` descriptor
   - See [FHIR Package specification](https://registry.fhir.org/learn) for more details
2. Go to **Manage IGs**.
3. Click **Upload Local IG** and select your `.tgz` file.
4. The toolkit will extract and register the IG for use in validation.

> Useful for testing custom or unpublished IGs.

## 4. Validating FHIR Resources

### Steps

1. Go to the **Validation** section.
2. Upload your FHIR resource file (JSON or XML).
3. Select the IG to validate against (imported or uploaded).
4. Click **Validate**.
5. Review the validation report showing errors, warnings, and info messages.
6. **Recommended**: Click the **Process** button to analyze and display additional requirements information implied by the package:
   - Optional elements that could be included
   - Must-support elements that implementers are required to understand
   - This analysis helps ensure complete implementation of the IG requirements

> Lite Mode uses local StructureDefinitions only. Terminology validation (e.g., ValueSet bindings) may be limited.