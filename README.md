## Overview

`MolDef-Spec-python` provides a Python-based implementation of the HL7 FHIR MolecularDefinition resource, including structured profile definitions for **Allele** and **Sequence**. These profiles represent constrained, use-case-specific views of the base resource, aligned with ongoing work in FHIR.

This repository reflects the **schema modeling component** of our broader genomics tooling effort. While it is not intended to function independently, it contains the core definitions used to construct MolecularDefinition resources within larger applications.

---

### Looking to Use This Code?

This repository contains a standalone copy of the core schema and profile definitions used in the [FHIR-MolDef-python](https://github.com/InformaticsGenomicMedicine/FHIR-MolDef-python) project.

It has been separated into its own repository to reflect the modular structure of our tooling suite and to highlight the specific modeling work related to the MolecularDefinition resource and its Sequence and Allele profiles.

If you are looking to use or explore this code in practice, including fully functional examples, test coverage, and interactive notebooks, please visit the main implementation repository:

[FHIR-MolDef-python](https://github.com/InformaticsGenomicMedicine/FHIR-MolDef-python)

There you will find:

- Integrated usage of models and translation logic  
- Example notebooks with real-world scenarios  
- A complete test suite for validation

---

## Acknowledgments
This project relies on the following packages and resources. We extend our gratitude to their respective developers and contributors for making these tools freely available:

- **[HL7 FHIR](https://hl7.org/fhir/6.0.0-ballot2/moleculardefinition.html)**
- **[fhir.resource](https://github.com/nazrulworld/fhir.resources)**
- **[fhir-core](https://github.com/nazrulworld/fhir-core)**