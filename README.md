# AI-based Resume Screening for Cultural Fit

This project leverages Natural Language Processing (NLP) and Machine Learning to evaluate resumes for cultural fit within an organization. By analyzing textual patterns in resumes and comparing them with known successful employee profiles, the system helps streamline hiring and promote organizational alignment.

## 📌 Project Objective

- Predict whether a candidate is a cultural fit based on their resume text.
- Reduce bias and increase hiring efficiency through AI-driven automation.
- Improve team cohesion by aligning new hires with company values.

## 🧠 Methodology

1. **Data Preparation**: Text resumes labeled as cultural fit (1) or not (0).
2. **Text Processing**: Cleaning and TF-IDF vectorization of resume content.
3. **Model Training**: Logistic Regression and Random Forest for prediction.
4. **Evaluation**: Classification metrics and confusion matrix visualization.

## 📁 Project Structure

```
AI-Resume-Screening/
│
├── data/
│   └── resumes.xlsx                # Input dataset with resumes and labels
├── scripts/
│   └── resume_fit_model.py        # Core training and evaluation script
├── figures/
│   └── confusion_matrix.png       # Visual evaluation output
├── requirements.txt               # Python dependencies
└── README.md                      # Project documentation
```

## 🚀 How to Run

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Ensure your dataset (`resumes.xlsx`) is in the `/data` folder.**

3. **Run the model**
   ```bash
   python scripts/resume_fit_model.py
   ```

4. **Results**
   - Accuracy and classification report printed in the console.
   - Confusion matrix and feature importance plots saved in `/figures`.

## 🔧 Technologies Used

- Python
- Scikit-learn
- Pandas
- TF-IDF Vectorizer (NLP)
- Matplotlib, Seaborn

## 📊 Output Examples

- Confusion Matrix: Visual check on model prediction accuracy.
- Feature Importance: Which resume features are most influential.

## 🧠 Future Work

- Integrate BERT embeddings for deeper semantic understanding.
- Develop a Streamlit interface for uploading and screening resumes.
- Add explainability via SHAP or LIME.

## 👤 Author

**Okes Imoni**  
