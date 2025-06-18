# MPPO

Manufacturing Process Parameter Ontology

This repository provides a base structure for projects combining ontology files with machine learning code.

## Repository layout

- `ontology/` – contains OWL files for the Manufacturing Process Parameter Ontology. The existing `MPPO.owl` file is located here.
- `ml/` – placeholder for all machine learning scripts and notebooks. The directory currently contains a `.gitkeep` file so it is tracked by Git.
- `requirements.txt` – Python dependencies commonly used for ML and ontology processing.
- `.gitignore` – rules for ignoring build artifacts and local environment files.

## Getting started

1. Create a Python virtual environment and install dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

2. Add your ontology files to the `ontology` directory.
3. Place notebooks and ML code inside the `ml` directory.

Feel free to modify this structure as the project grows.
