# 🩺 Sleep Disorder Classification Project  

This project analyzes a **mini-database** of clinical and professional data from patients to categorize their **sleep disorders**. The workflow includes:  
1. **Feature Engineering**: Transforming raw data into a format consumable by machine learning models.  
2. **Model Training and Testing**: Implementing and comparing the performance of four classification algorithms:  
   - K-Nearest Neighbors (KNN)  
   - Gaussian Naive Bayes  
   - Random Forest  
   - Decision Tree  

---

## 🚀 Getting Started  

### Prerequisites  
Ensure you have **Python 3.8+** installed on your system.  

### Installation  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/sleep-disorder-classification.git
   cd sleep-disorder-classification
   ```  

2. **Create a Virtual Environment (Optional but Recommended)**  
   ```bash
   python -m venv env
   source env/bin/activate  # Linux/Mac
   env\Scripts\activate     # Windows
   ```  

3. **Install Dependencies**  
   Install the necessary Python libraries from the `requirements.txt` file:  
   ```bash
   pip install -r requirements.txt
   ```  

---

## 🧠 Workflow  

1. **Feature Engineering**  
   - Transform clinical data into features suitable for machine learning models.  
   - Includes handling missing values, encoding categorical data, and scaling numerical data.  

2. **Model Implementation**  
   - Train and test four classifiers:  
     - K-Nearest Neighbors (KNN)  
     - Gaussian Naive Bayes  
     - Random Forest  
     - Decision Tree  
   - Compare performance metrics (accuracy, precision, recall, F1-score).  

3. **Evaluation**  
   - Analyze model predictions to identify the best-performing algorithm.  

---