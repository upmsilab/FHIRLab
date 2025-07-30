---
# Page settings
layout: default
keywords: FHIRFLARE, FSH, FHIR Shorthand, Conversion, Implementation Guide
comments: false

# Hero section
title: FHIRFLARE FSH Converter
description: "A browser-based toolkit for converting FHIR resources to FSH (FHIR Shorthand)"

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
        content: FHIRFLARE Validation
        url: '../FHIRFLARE_Validation_Guide'
    next:
        content: HAPI Server
        url: '../HAPI'

---

# FHIRFLARE FSH Converter – Quick Start Guide

**Hosted at:** [https://flare.fhirlab.net](https://flare.fhirlab.net)  
**Audience:** Implementation Guide authors and FHIR developers

## 1. Accessing the FSH Converter

- Open your browser and go to: [https://flare.fhirlab.net](https://flare.fhirlab.net)
- Navigate to the **FSH Converter** section from the main menu.
- No installation required — conversion runs entirely in your browser.

## 2. What is FSH?

FHIR Shorthand (FSH) is a domain-specific language for defining FHIR Implementation Guides:

- Simpler, more concise syntax than raw FHIR JSON/XML
- Human-readable and writable
- Designed for creating and maintaining Implementation Guides
- Compiled to FHIR artifacts using SUSHI

> **Learn more about FSH**: Visit the [FSH School website](https://fshschool.org/) for comprehensive documentation, tutorials, and examples. The [FSH Quick Reference](https://build.fhir.org/ig/HL7/fhir-shorthand/FSHQuickReference.pdf) is also an excellent resource for syntax details.

## 3. Converting FHIR Resources to FSH

### Steps

1. Navigate to the **FSH Converter** section.
2. Upload one or more FHIR resource files (JSON or XML).
3. Configure conversion options:
   - Output style (flat or grouped)
   - Include metadata
   - Use alias file
4. Click **Convert**.
5. Review the generated FSH in the preview pane.
6. Download the generated `.fsh` files for use with SUSHI.

> Powered by the integrated **GoFSH** engine for accurate FSH generation.

## 4. Advanced Configuration Options

### Available Options

- **Flatten FSH**: Generates a single FSH file regardless of input size
- **Include Metadata**: Adds helpful comments and metadata to the FSH output
- **Use Alias File**: Generates a separate aliases.fsh file with common references
- **Include Code Systems**: Includes CodeSystem definitions in the output

### Best Practices

- For smaller resources, use flattened mode for easier reading
- For complex resources, use grouped mode to organize by resource type
- Always include metadata for better documentation
- Use alias files when working with multiple interdependent resources