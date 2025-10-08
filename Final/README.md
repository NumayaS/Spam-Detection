# Spam Email Dataset

## Overview
This dataset contains emails labeled as either **ham (legitimate)** or **spam (junk email)**.

- **Columns**  
  - `text`: The content of the email  
  - `spam`: Label (0 = ham, 1 = spam)  

## Labels
- **0 → Ham**: Normal, non-spam emails  
- **1 → Spam**: Junk or unwanted emails  

## Feature Extraction Ideas
Students may extract features such as:
- Email length (characters, words)  
- Frequency of special characters (`!`, `$`, etc.)  
- Presence of keywords (e.g., *free, win, offer*)  
- Word frequency or TF-IDF values  

## Visualization Ideas
- Distribution of email lengths (spam vs. ham)  
- Word clouds for spam and ham  
- Histogram of keyword frequencies  

---

## Project Setup & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/NumayaS/Spam-Detection.git
cd Spam-Detection/Final
```

### 2. Create and Activate Conda Environment
```bash
conda create -n spam-detect python=3.10
conda activate spam-detect
```

### 3. Install Required Packages
```bash
pip install -r requirements.txt
# Or manually install needed packages:
pip install numpy pandas scikit-learn joblib
```

### 4. Preprocessing
Run the preprocessing scripts/notebooks to clean and prepare the data:
```bash
# Example (if script exists):
python hd_project/data/preprocess.py
# Or open and run the notebook:
jupyter notebook hd_fits_all.ipynb
```

### 5. Training
Run the training script or notebook:
```bash
# Example (if script exists):
python hd_project/train.py
# Or open and run the notebook:
jupyter notebook hd_fits_all.ipynb
```

---

**Note:** Adjust script/notebook names as needed for your workflow.
