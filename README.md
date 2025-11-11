#  Human Action Detection using Machine Learning

This project classifies human actions (like walking, running, sitting, etc.) based on extracted motion or pose data using **Machine Learning** techniques.  
It focuses on feature-based data preprocessing, model training, and performance evaluation to accurately identify human activities.

---

##  Features
- Data preprocessing, cleaning, and feature scaling using StandardScaler and RobustScaler  
- Label encoding and resampling techniques to handle class imbalance  
- Model training using multiple algorithms such as Logistic Regression, Random Forest, and SVM  
- Evaluation based on **accuracy**, **precision**, **recall**, and **F1-score**  
- Data visualization for feature distribution and model performance  

---

##  Files Included
| File | Description |
|------|--------------|
| `HUMAN_ACTION_DETECTION.ipynb` | Jupyter Notebook containing code for preprocessing, training, and evaluation |
| `README.md` | Project documentation and setup guide |

---

##  Requirements
Install dependencies before running the notebook:
```bash```
pip install numpy pandas scikit-learn matplotlib seaborn

##  Dataset
The dataset used in this project contains structured data representing human motion or activity information.  
Each record includes features such as:
- Joint coordinates, acceleration, or sensor readings  
- Body posture and movement-related data  
- Target labels indicating actions like walking, sitting, running, or jumping  
.

---

##  Model Workflow
1. **Data Loading:** Import and explore the dataset.  
2. **Preprocessing:** Handle missing values, encode categorical features, and scale numerical data using StandardScaler/RobustScaler.  
3. **Balancing:** Address class imbalance using resampling or SMOTE.  
4. **Model Training:** Train and compare multiple machine learning algorithms including Logistic Regression, Random Forest, and SVM.  
5. **Evaluation:** Evaluate model performance using Accuracy, Precision, Recall, and F1-Score metrics.  
6. **Visualization:** Plot data distributions and confusion matrices for analysis and insight.

---

##  Results
- Achieved **~90% overall model accuracy** on the test dataset.  
- Improved recall by **12%** using SMOTE for class balance.  
- Generated performance reports and confusion matrices for model comparison.  

---

##  How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "HUMAN_ACTION_DETECTION.ipynb"

