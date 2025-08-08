# Disease_Diagnosis_Platform
The Disease Diagnosis Platform allows users to input health-related parameters and receive predictions about potential diseases. It integrates multiple ML models into one interactive web interface.

DiseaseDiagnosisPlatform/
│
├── code/
│   ├── __init__.py
│   ├── DiseaseModel.py
│   ├── helper.py
│   ├── train.py
│   └── data/
│       ├── clean_dataset.tsv
│       ├── dataset.csv
│       ├── lung_cancer.csv
│       ├── symptom_Description.csv
│       ├── symptom_precaution.csv
│       └── Symptom-severity.csv
│
├── disease_prediction_env/       # Virtual environment (optional)
├── models/                       # Trained model files (.pkl)
│
├── app.py                        # Main Streamlit app
├── requirements.txt              # Python dependencies
├── data.db                       # SQLite database (if used)
│
├── assets/                       # (Optional) move all images here
│   ├── logo.png
│   ├── heart.jpg
│   ├── liver.jpg
│   ├── lung.jpg
│   ├── negative.jpg
│   ├── positive.jpg
│   ├── d3.jpg
│   ├── h.png
│   ├── j.jpg
│   ├── heart2.jpg
│   └── 63.gif
│
└── README.md
---

## ⚙️ Setup Instructions

### ✅ Prerequisites

- Python 3.8 or above  
- Git installed  
- pip (Python package manager)

---

### 💻 Installation Steps

```bash
# 1. Clone the repository

# 2. Create and activate virtual environment
python -m venv venv

# For Windows
venv\Scripts\activate

# For Linux/Mac
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run app.py
