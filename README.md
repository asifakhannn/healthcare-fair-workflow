# TikTok Content Marketing – FAIR Reproducible Workflow

This repository analyzes how **TikTok content marketing** impacts **brand awareness, engagement, and purchase intention** for local fashion brands.


tiktok-fair-workflow/
├─ dataset/                # dataset here
    └─ DOI-15666301.json
├─ notebook.ipynb/         # analysis + FAIR notes  
├─ environment.yml      # reproducible environment
├─ README.md            # instructions
└─ LICENSE              # open license


- **Dataset Source (Zenodo DOI):** [10.5281/zenodo.15666301](https://doi.org/10.5281/zenodo.15666301)  
- **Goal:** demonstrate a clean, reproducible workflow that follows the **FAIR principles** (Findable, Accessible, Interoperable, Reusable).

---

## 🔁 Reproduce this project

### 1. Clone
```bash
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

## 📖 Citation

If you use this dataset, please cite as:

Mohammad, S. S. (2025). *Impact of Tiktok Content Marketing on Brand Awareness, Engagement and Purchase Intention in Local Fashion* [Data set]. International Conference on Sustainable Collaboration in Business, Technology, Information and Innovation. Zenodo. [https://doi.org/10.5281/zenodo.15666301](https://doi.org/10.5281/zenodo.15666301)

APA format is provided above. Other citation styles are available on the Zenodo page.

---

## License

- **Dataset License**: Creative Commons Attribution 4.0 International (CC BY 4.0).  
  This means you are free to share and adapt the data, as long as you give appropriate credit.  

- **Code in this Repository**: MIT License (see `LICENSE` file).  



FAIR Mapping
	•	Findable: dataset has a DOI, repo is public on GitHub.
	•	Accessible: data downloadable, workflow open-source.
	•	Interoperable: CSV/JSON format, standard Python libraries.
	•	Reusable: clear environment, README, and license (MIT recommended).


Reproducibility & Versioning
	•	SemVer: tag releases v1.0.0, v1.1.0, etc.
	•	Environment pinning: exact versions in environment.yml.
	•	Git: commit history keeps track of changes.
