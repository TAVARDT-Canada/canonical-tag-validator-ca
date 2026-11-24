# Canonical Tag and URL Consolidation Validator

[![Canonical Tag Validator](https://img.shields.io/badge/TAVARDT-Canonical-5b3cf5.svg)](https://tools.tavardt.com/ca/canonical-tag-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Audits canonical URLs, bilingual link alignment, protocol consistency, and search indexing integrity.

Developed and maintained by the technical search architecture division of **TAVARDT Canada**.

***

## Canonical Tag Audit Capabilities

* **Canonical Directive Inspection**: Audits `<link rel="canonical">` tags across bilingual English and French web structures.
* **Duplicate Tag Prevention**: Detects conflicting or multiple canonical tags declared on a single document.
* **Absolute URL Verification**: Ensures canonical directives use absolute paths with secure HTTPS protocols.
* **Destination Response Verification**: Verifies that the canonical target URL returns an HTTP 200 OK status code.
* **Consolidation Health Score**: Quantitative 0 to 100 health score with prioritized technical remediation steps.

***

## Installation and Execution

Requires Python 3.8 or higher.

```bash
git clone https://github.com/TAVARDT-Canada/canonical-tag-validator-ca.git
cd canonical-tag-validator-ca
python canonical_validator.py https://company.ca
```

To output results in structured JSON format:

```bash
python canonical_validator.py https://company.ca -json
```

***

## Comprehensive Web Diagnostic

For full web verification and deep URL consolidation audits:

* **Official Canonical Tag Checker Tool**
* **TAVARDT Canada Enterprise Portal**

***

## Technical SEO and Indexation Advisory

For Canadian federal and enterprise platforms aligning with W3C Standards and Canadian Digital Guidelines, contact the specialists at **TAVARDT Canada**.
