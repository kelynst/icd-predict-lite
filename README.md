# 🩺 ICD Predict Lite

A simplified project exploring how to predict ICD codes (medical billing codes) from clinical notes using Python.  
This repo is meant as a **learning + demo project** for automation and healthcare data workflows.

---

## 📌 Project Overview
- **Goal** → Explore how free-text clinical notes can be connected to ICD codes  
- **Approach** → Work with preprocessing, text handling, and basic machine learning  
- **Status** → Early-stage experiment ("Lite" version – not a production model)

---

## 📂 Repo Structure
icd-predict-lite/
│── notebooks/         # Jupyter notebooks with experiments
│── requirements.txt   # Dependencies
│── README.md          # Project documentation (this file)
│── src/               # Source code (data prep, features, model, predict)
│── tests/             # Simple smoke tests
│── examples/          # Example notebooks
- **notebooks/** → Jupyter notebooks where the experiments and model testing live.  
- **requirements.txt** → A list of Python packages to install for reproducibility.  
- **README.md** → This documentation file you’re reading.  
- **src/** → Python scripts for preprocessing, feature engineering, model, and predictions.  
- **tests/** → Minimal tests to confirm setup works.  
- **examples/** → Quickstart notebook(s).  

---

## 🚀 Getting Started
Follow these steps to set up the project locally:

### 1. *Clone the repository*
Clone this repo from GitHub onto your local machine.
```bash
git clone https://github.com/kelynst/icd-predict-lite.git
cd icd-predict-lite
```

### 2. *Create a virtual environment*
Set up an isolated Python environment for dependencies.
```bash
python3 -m venv .venv
```

### 3. *Activate the virtual environment*
Enable the environment so Python and pip use the local versions.

- **macOS/Linux**
  ```bash
  source .venv/bin/activate
  ```
- **Windows (PowerShell)**
  ```powershell
  .venv\Scripts\Activate
  ```

### 4. *Upgrade pip*
Make sure pip is up to date.
```bash
pip install --upgrade pip
```

### 5. *Install dependencies*
Install the required Python packages listed in `requirements.txt`.
```bash
pip install -r requirements.txt
```

### 6. *Launch Jupyter Notebook*
   Start Jupyter inside the virtual environment to explore the notebooks.  
   ```bash
   jupyter notebook

   ---
## 📈 Next Steps
- Add example notebooks under `/examples`
- Expand preprocessing in `/src`
- Add simple tests in `/tests`