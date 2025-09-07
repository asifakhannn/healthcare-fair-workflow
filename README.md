# Kaggle Healthcare Dataset – FAIR Reproducible Workflow


This repository analyzes a **Healthcare Dataset** that includes patient-level healthcare data (age, gender, medical conditions, treatment cost, etc.).  
The goal is to show how a simple data science project can be made **FAIR**: Findable, Accessible, Interoperable, and Reusable.

---

## Dataset
- **Name:** Healthcare Dataset (`healthcare.csv`)  
- **Content:** Patient demographics, admission details, billing amounts, and medical information.  
- **Preprocessing:** Derived features such as `length_of_stay` and `age_bin` were created for analysis.  
- **Source:** [Kaggle Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)

---

## Repository Structure

Healthcare-fair-workflow/
├─ dataset/                # dataset here
    └─ healthcare.csv
├─ output/                # analytics output here
    └─ healthcare_clean_subset.csv
├─ notebook.ipynb/         # analysis + FAIR notes  
├─ environment.yml      # reproducible environment
├─ README.md            # instructions
└─ LICENSE              # open license


- **Dataset Source:** [Kaggle Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)
  
- **Goal:** demonstrate a clean, reproducible workflow that follows the **FAIR principles** (Findable, Accessible, Interoperable, Reusable).

---

---

##  Environment Setup
All dependencies are defined in [`environment.yml`](environment.yml).

```bash
# 1. Create environment
conda env create -f environment.yml
conda activate healthcare_fair_env

# 2. Clone repository
git clone https://github.com/asifakhannn/healthcare-fair-workflow.git
cd healthcare-fair-workflow

# 3. Add dataset
# Download from Kaggle and save to dataset/
# https://www.kaggle.com/datasets/prasad22/healthcare-dataset

# 4. Run Jupyter
jupyter lab



---

## Usage Guidelines
- Open the `notebook.ipynb` notebook to start the analysis.
- Follow the instructions in the notebook to run the code cells and generate outputs.
- Ensure that the required data files are placed in the `dataset` directory.

## Dependencies
The project relies on several Python packages for data analysis and visualization. These dependencies are specified in the `environment.yml` file. Version pinning is used to ensure compatibility and reproducibility across different environments.


## FAIR Data Principles
This workflow is designed with the FAIR principles in mind:
- **Findable**: The project is hosted on GitHub with clear documentation and metadata.
- **Accessible**: The data is included in the repository and can be easily loaded using the provided functions.
- **Interoperable**: The project uses widely accepted formats (CSV for data, PNG for outputs) and standardizes column names.
- **Reusable**: The code is licensed and includes documentation for context and assumptions, making it easy to adapt for other datasets.


## Risk Assessment
- **Upstream Availability**: Datasets may change or become unavailable. To mitigate this, consider archiving the dataset or including it in the repository Available at: [https://www.kaggle.com/datasets/prasad22/healthcare-dataset]
- **Package Changes**: Future updates to packages may introduce breaking changes. Version pinning in `environment.yml` helps manage this risk.
- **Data Quality**: Inconsistent data can affect results. Basic cleaning and validation steps are included in the workflow to address this issue.



FAIR Mapping
	•	Findable: dataset has a DOI, repo is public on GitHub.
	•	Accessible: data downloadable, workflow open-source.
	•	Interoperable: CSV/JSON format, standard Python libraries.
	•	Reusable: clear environment, README, and license.


Reproducibility & Versioning
	•	SemVer: tag releases v1.0.0, v1.1.0, etc.
	•	Environment pinning: exact versions in environment.yml.
	•	Git: commit history keeps track of changes.



##  Citation

If you use this dataset, please cite as:

prasad22. (2021). *Healthcare Dataset* [Data set]. Kaggle.  
Available at: [https://www.kaggle.com/datasets/prasad22/healthcare-dataset]

Note: This dataset does not provide a DOI. For improved Findability and citability, this repository can be archived in Zenodo, which will mint a DOI.

## License

- **Dataset License:** Provided on Kaggle. Unless otherwise stated, Kaggle datasets are typically released under open licenses (often CC0/Public Domain). 
- **Code in this Repository:** MIT License 


