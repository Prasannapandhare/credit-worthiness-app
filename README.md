# **Credit Card Worthiness Prediction App**
This project was developed as part of an internship at **Celebal Technologies - CSI'24**.  
<a href="https://credit-worthiness-app.onrender.com/" target="_blank">Live Link</a>

---

## 📍 **Project Overview**
This web application empowers users to predict their credit card worthiness by inputting financial and personal details. Built with a robust machine learning model trained on comprehensive datasets, the app ensures accurate and reliable predictions. The project uses Flask for the backend and HTML, CSS, and JavaScript for the frontend, incorporating Jupyter notebooks for data analysis and model building. 
- Discover your credit worthiness with our sophisticated prediction tool designed to deliver precise results.

### 🚀 Introduction
The Credit Card Worthiness Prediction App uses a machine learning model to assess the creditworthiness of individuals. The model is trained on various financial and personal data points to provide an accurate prediction. Ideal for credit scoring and financial risk assessment.
- ### German Credit Data 📄
  - #### Overview
    The German Credit dataset, provided by Prof. Dr. Hans Hofmann (University of Hamburg), is used to classify individuals as good or bad credit risks.
  - #### Details
    - **Instances:** 1000
    - **Attributes:**
        - Original: 20 (7 numerical, 13 categorical)
        - Numerical: 24 (all numerical)
  - #### Source
    <a href="https://archive.ics.uci.edu/ml/datasets/Statlog+(German+Credit+Data)" target="_blank">German Credit Data - UCI Repository</a>

### 🗂️ Folder Structure
```
credit-worthiness-app  
│
└─── datasets
│   |   Index
|   |   german.data
|   |   german.data-numeric
|   |   german.doc
│   └── processed.csv
└─── notebooks
│   |   Project.ipynb
│   └── app.ipynb
└─── static
│   └── css
|   |      |   style_index.css
|   |      └── style_result.css
│   └── images
|          |   dropdown.png
|          └── favicon.png
└─── templates
│   |   index.html
│   └── result.html
└─── app.py
└─── README.md
└─── Procfile
└─── random_forest_model.pkl
└─── requirements.txt
└─── runtime.txt

```

### 🔧  Tech Stack
  - **Backend**: Flask  
    ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
  - **Frontend**: HTML, CSS, JavaScript  
    ![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
    ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  - **Data Analysis and Model Building**: Jupyter Notebooks  
    ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### ⚙️ Installation
  To run this project locally, follow these steps:
  1. **Clone the repository:**
      ```sh
      git clone https://github.com/Prasannapandhare/credit-worthiness-app.git
      cd credit-card-worthiness-app
      ```
  2. **Install the dependencies:**
      ```sh
      pip install -r requirements.txt
      ```
  3. **Run the Flask app:**
      ```sh
      flask run
      ```
  4. **Open your browser and go to:**
      ```
      http://127.0.0.1:5000
      ```

### 🤖 Usage
  1. **Navigate to the homepage.**
  2. **Enter the required details to assess creditworthiness.**
  3. **Submit the form to get the prediction results.**

### 🧩 Features
  - User-friendly interface to input financial and personal information
  - Real-time prediction of credit card worthiness
  - Data visualization and analysis using Jupyter notebooks
  - Secure and efficient handling of user data
  - Interactive charts and graphs to help users understand their credit standing

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)]()
### ➤ Index (Home) Page
![image](https://github.com/user-attachments/assets/3227f0a1-ddec-4bc4-8427-39ebf3c137a1)
[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)]()
### ➤ Result Pages
#### 🧪 Credit Worthiness Prediction Demo
For demonstration purposes, you can use the following inputs to predict credit worthiness.These inputs illustrate different scenarios of credit worthiness. Use these examples to test the prediction model and see how it evaluates the credit status based on the given data. 
> [!NOTE]
> <sub>These inputs are taken directly from the top two rows of our dataset.</sub>
##### Example Inputs
###### Good Credit
- Checking account status: A11
- Duration: 6 months
- Credit history: A34
- Purpose: A43
- Credit amount: 1169
- Savings account/bonds: A65
- Employment: A75
- Installment rate: 4
- Personal status and sex: A93
- Other debtors / guarantors: A101
- Present residence since: 4
- Property: A121
- Age: 67
- Other installment plans: A143
- Housing: A152
- Number of existing credits: 2
- Job: A173
- Number of people liable: 1
- Telephone: A192
- Foreign worker: A201 <br><br>
![image](https://github.com/user-attachments/assets/f4516185-06b8-43e6-836a-24cf11d8a897)


###### Bad Credit
- Checking account status: A12
- Duration: 48 months
- Credit history: A32
- Purpose: A43
- Credit amount: 5951
- Savings account/bonds: A61
- Employment: A73
- Installment rate: 2
- Personal status and sex: A92
- Other debtors / guarantors: A101
- Present residence since: 4
- Property: A121
- Age: 22
- Other installment plans: A143
- Housing: A152
- Number of existing credits: 1
- Job: A173
- Number of people liable: 1
- Telephone: A191
- Foreign worker: A201 <br><br>
![image](https://github.com/user-attachments/assets/e5daf5c4-da39-4fac-b190-6acee9fc6d63)
[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)]()

---    
#### 🔰 *Project Developer* 🧑‍💻
- **Name**: Prasanna Pandhare  
- **Email**: prasannapandhare20160@gmail.com  
- **GitHub**: [Prasannapandhare](https://github.com/Prasannapandhare)
