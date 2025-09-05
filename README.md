# Kaggle Healthcare Dataset – FAIR Reproducible Workflow

This repository analyzes how **Healthcare Dataset** includes Patient-level healthcare data (age, gender, medical conditions, treatment cost, etc. The goal is to show how a simple data science project can be made **FAIR**: Findable, Accessible, Interoperable, and Reusable.


Healthcare-fair-workflow/
├─ dataset/                # dataset here
    └─ healthcare.csv
├─ notebook.ipynb/         # analysis + FAIR notes  
├─ environment.yml      # reproducible environment
├─ README.md            # instructions
└─ LICENSE              # open license


- **Dataset Source:** [Kaggle Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)
  
- **Goal:** demonstrate a clean, reproducible workflow that follows the **FAIR principles** (Findable, Accessible, Interoperable, Reusable).

---

## 🔁 Reproduce this project

```bash
### 1. Clone
git clone https://github.com/asifakhannn/tiktok-fair-workflow.git
cd tiktok-fair-workflow

### 2. Create environment (Conda)
conda env create -f environment.yml
conda activate tiktok_fair_env

###3. Put the dataset
Save the dataset file (DOI-15666301.json or CSV from Zenodo) inside data/.

###4. Run the notebook
jupyter lab


---


FAIR Mapping
	•	Findable: dataset has a DOI, repo is public on GitHub.
	•	Accessible: data downloadable, workflow open-source.
	•	Interoperable: CSV/JSON format, standard Python libraries.
	•	Reusable: clear environment, README, and license (MIT recommended).


Reproducibility & Versioning
	•	SemVer: tag releases v1.0.0, v1.1.0, etc.
	•	Environment pinning: exact versions in environment.yml.
	•	Git: commit history keeps track of changes.



##  Citation

If you use this dataset, please cite as:

prasad22. (2021). *Healthcare Dataset* [Data set]. Kaggle.  
Available at: [https://www.kaggle.com/datasets/prasad22/healthcare-dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)

Note: This dataset does not provide a DOI. For improved Findability and citability, this repository can be archived in Zenodo, which will mint a DOI.

## License

- **Dataset License:** Provided on Kaggle. Unless otherwise stated, Kaggle datasets are typically released under open licenses (often CC0/Public Domain). 
- **Code in this Repository:** MIT License 


