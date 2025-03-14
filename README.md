# **README: Mycotoxin Prediction in Corn Using Machine Learning**

## **1. Setup Instructions**

### **1.1 Install Dependencies**
Ensure you have Python installed (recommended version: **Python 3.8+**). Install the required dependencies using:

```bash
pip install -r requirements.txt
```

Alternatively, you can install dependencies manually:
```bash
pip install numpy pandas scikit-learn xgboost matplotlib seaborn jupyterlab
```

### **1.2 Running the Code**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
   ```
2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the desired notebook and run all cells.

---

## **Repository Structure**
This repository contains all necessary files for training and evaluating machine learning models for predicting mycotoxin (DON concentration) in corn using spectral data.

### **Notebooks**
There are two Jupyter notebooks used for different preprocessing methods:
1. **Notebook 1:** Uses **log transformation** for handling target variable skewness.
2. **Notebook 2:** Uses **IQR-based clipping method** for handling extreme values.

### **Reports**
Each notebook has a corresponding report summarizing the results:
1. **Report1:** Corresponding to the **log transformation notebook**.
2. **Report2:** Corresponding to the **clipping method notebook**.

Both reports are available in **PDF format** as well.

## **2. Files in the Repository**
```
📄 README.md              # Instructions and setup guide
📄 requirements.txt       # List of dependencies
📄 TASK-ML-INTERN.csv     # Dataset file
📄 Log_Transformation.ipynb  # Notebook using log transformation
📄 Clipping_Method.ipynb     # Notebook using IQR-based clipping method
📄 Report1.pdf            # Report corresponding to log transformation notebook
📄 Report2.pdf            # Report corresponding to clipping method notebook
```

---

## **3. Additional Notes**
- **Dataset:** Ensure that `TASK-ML-INTERN.csv` is in the same directory before running the notebooks.
- **Customization:** Modify the notebooks to adjust hyperparameters for tuning models.
- **Results & Analysis:** Both notebooks contain visualizations and performance metrics.

For any issues, please open an issue in the repository or contact the author.

---








