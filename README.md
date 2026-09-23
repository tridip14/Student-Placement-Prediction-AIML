# Student Placement Prediction using Machine Learning

**IBM SkillsBuild Data Analytics with AI Internship 2026**

## Project Description
This project demonstrates an end-to-end AI/ML workflow for predicting a student's placement outcome from academic and profile-related features.

The project uses a **synthetically generated dataset** inside the Jupyter Notebook. This makes the project reproducible without requiring access to private student records or a third-party dataset.

## Aim
To analyze student data and build supervised machine-learning models that classify a student as:
- `1` = Placed
- `0` = Not Placed

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Logistic Regression
- Random Forest

## Features
- CGPA
- Attendance
- Study hours per day
- Number of projects
- Number of internships
- Coding score
- Department
- Communication level

## Files
- `Aklabya_StudentPlacementPrediction.ipynb` — complete project code and analysis
- `requirements.txt` — Python dependencies
- `Aklabya_StudentPlacementPrediction_ProjectReport.docx` — project report
- `README.md` — project overview and run instructions

## Dataset
The notebook generates the dataset programmatically using NumPy with a fixed random seed. Therefore, there is no external dataset URL required for this demonstration.

**Important:** The generated dataset is synthetic and does not represent real students. It should not be used for actual admissions, hiring, placement, or other high-impact decisions.

## How to Run

### 1. Install Python
Use Python 3.10 or newer.

### 2. Create a virtual environment (optional)
```bash
python -m venv venv
```

Windows:
```bash
venv\Scripts\activate
```

Linux/macOS:
```bash
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Start Jupyter
```bash
jupyter notebook
```

Open:
`Aklabya_StudentPlacementPrediction.ipynb`

Then select **Kernel → Restart & Run All**.

## Expected Output
The notebook produces:
- dataset preview and summary
- missing-value analysis
- placement distribution chart
- feature comparisons
- department-wise placement visualization
- model comparison table
- classification report
- confusion matrix
- ROC curves
- example prediction with probability

## Future Scope
- Use a properly collected real-world dataset
- Add cross-validation and hyperparameter tuning
- Add SHAP/LIME explainability
- Perform fairness and bias checks
- Build a Streamlit web dashboard
- Save the trained model with joblib

## Disclaimer
This is an educational project. The synthetic model and its predictions are not evidence about real-world student placement outcomes.
