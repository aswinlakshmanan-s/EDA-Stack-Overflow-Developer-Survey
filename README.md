# 📊 Analysis of Job Factors in the Tech Industry – Stack Overflow Developer Survey

## 📌 Project Overview  
This project aims to analyze the **importance of various job factors** in the tech industry—such as **remote work, company culture, and career development opportunities**—using data from the **2020 Stack Overflow Developer Survey**. By identifying key trends and patterns, this study helps organizations tailor their strategies to attract and retain top tech talent.  

## 👥 Team Members  
- **Prashanth Baskar**  
- **Bhuvan Dama Venkatesh Raj**  
- **Aswin Lakshmanan**  
- **Kaviprakash Ramalingam**  

## 🎯 Objectives  
- Identify the **most important job factors** for tech professionals.  
- Analyze which job factors **tend to be chosen together**.  
- Discover patterns and trends based on **demographics, experience, and job satisfaction**.  

---

## 📂 Dataset Information  
- **Source**: [Stack Overflow Developer Survey 2020](https://insights.stackoverflow.com/survey/2020)  
- **Timeframe**: Conducted between **February 5th – 28th, 2020**  
- **Scope**: Includes responses from **tech professionals worldwide**  

### 📌 Key Data Columns  
| Column | Description |
|--------|------------|
| `JobFactors` | Most important job factors for respondents |
| `JobSat` | Job satisfaction rating |
| `JobSeek` | Current job-seeking status |
| `YearsCode` | Years of coding experience |
| `ConvertedComp` | Compensation in USD |
| `WorkRemote` | Remote work frequency |
| `Age` | Age of the respondent |
| `Gender` | Gender identity |

---

## 🔎 Exploratory Data Analysis (EDA)  
The following analyses were performed:  
✅ **Job Factors Distribution** – Understanding how frequently each factor is selected.  
✅ **Correlation Analysis** – Exploring relationships between job factors and demographic variables.  
✅ **Outlier Handling & Missing Values** – Ensuring clean and reliable data for modeling.  

---

## ⚙️ Data Preprocessing & Feature Engineering  
- **Handling Missing Values**: Filling, imputing, or removing NA values.  
- **Encoding Categorical Data**: Converting categorical values into numerical representations.  
- **Feature Engineering**: Creating new variables such as **years of coding experience** and **age at first code** to enhance insights.  

---

## 🤖 Machine Learning Model  
### 📌 Algorithm Used  
- **XGBoost Classifier** – Predicting **job factor preferences** based on different features.  

### 📌 Model Evaluation  
- **Accuracy**  
- **Precision & Recall**  
- **Feature Importance Analysis** using **SHAP (SHapley Additive ExPlanations)**  

---

## 📈 Key Findings  
- **Non-monetary factors** (like **remote work, career growth, and work-life balance**) play a crucial role in **job satisfaction**.  
- **Technology-related preferences** (like preferred **programming languages & frameworks**) heavily influence job choices.  
- Respondents fall into **at least four distinct preference groups**, each prioritizing **different factors**.  

---

## 🚀 How to Run the Project  
### 🔧 Prerequisites  
Ensure you have **Python 3.8+** installed along with the required libraries.  

### 📥 Installation  
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/tech-job-factors-analysis.git
   cd tech-job-factors-analysis
   
2. **Install Dependencies**
  ```bash
  pip install -r requirements.txt

3. **Download the Dataset**
  Access the dataset from Stack Overflow Insights.
  Save it as survey_results_public.csv inside the data/ folder.

4. **Run the Analysis**
  ```bash
  jupyter notebook
  Open job_factors_analysis.ipynb and run all cells.
