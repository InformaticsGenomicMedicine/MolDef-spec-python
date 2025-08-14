## Overview

`MolDef-spec-python` is a Python implementation of the **HL7 FHIR MolecularDefinition** resource, with structured profiles for **Allele** and **Sequence**. These profiles apply structural and semantic constraints to the base FHIR MolecularDefinition resource.

This repository contains the core schema for our broader genomics tooling ecosystem, along with example Jupyter notebooks that demonstrate how to create MolecularDefinition, Allele, and Sequence models in Python using **pydantic**. 

---
### Getting started

This project isn’t published on PyPI yet, but you can follow these steps to install it locally and explore the example notebooks.

```bash
# Clone the repository
git clone https://github.com/yourusername/MolDef-spec-python.git
cd MolDef-spec-python

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

**Exlporing the Jupyter Notebooks**
1. Navigate to the `notebooks` directory and open a notebook you want to run.
2. In the Jupyter interface, click **Select Kernel** (top-right).
3. In the pop-up, choose **Python Environment...** and select your virtual environment.
4. Once the correct kernel is selected, run the cells in the notebook to explore the examples.

---
### Roadmap & Integration Plans

We are in the process of packaging this repository so it can be installed as a standlone python package. Once published, it will serve as a dependency for [MolDef-VRS-Translator](https://github.com/InformaticsGenomicMedicine/MolDef-VRS-Translator), a tool that transaltes between **VRS 2.0 Allele** and **FHIR Allele Profile**. 

Currently, both the active schema definitions and the translation logic live in the [FHIR-MolDef-python](https://github.com/InformaticsGenomicMedicine/FHIR-MolDef-python) project.

We plan to release two packages: 

* Schema (FHIR MolecularDefinition, Allele, and Sequence models)
* Translator (VRS <-> FHIR model conversions). 

This modular approach lets you install only what you need.

---
### Acknowledgments
This project builds on the following packages and resources.

- **[HL7 FHIR](https://hl7.org/fhir/6.0.0-ballot2/moleculardefinition.html)**
- **[fhir.resource](https://github.com/nazrulworld/fhir.resources)**
- **[fhir-core](https://github.com/nazrulworld/fhir-core)**