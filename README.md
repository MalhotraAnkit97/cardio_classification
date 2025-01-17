<img width="878" alt="image" src="https://github.com/user-attachments/assets/2ed44603-5a55-485f-9312-745e7eb8bee4" />

# **Cardiovascular Disease Classification Project**

## **Project Overview**
This project focuses on building a predictive model for cardiovascular disease classification using the **Cardiovascular Disease Dataset**. The dataset contains medical and demographic information that helps identify the presence of cardiovascular diseases. The primary goal is to use machine learning techniques to predict disease occurrence and extract insights for better disease management.

---

## **Key Features**
- **Disease Prediction**: Predicts the likelihood of cardiovascular disease based on patient data.
- **Risk Factor Analysis**: Identifies significant predictors like BMI, blood pressure, and glucose levels.
- **Data Visualization**: Provides insights through visual analysis of numerical and categorical predictors.
- **Future Extensions**: Proposes implementing advanced classification techniques like SVMs, neural networks, and integration with physical devices for real-time predictions.

---

## **Dataset Overview**
- **Source**: Cardiovascular Disease Dataset
- **Size**: 70,000 records, 13 variables
- **Target Variable**: `cardio`
  - `1`: Presence of cardiovascular disease
  - `0`: Absence of cardiovascular disease
- **Types of Data**:
  - **Objective**: Facts about patients (e.g., age, gender).
  - **Examination**: Medical examination results.
  - **Subjective**: Self-reported information.

---

## **Project Workflow**
1. **Data Preparation**:
   - Converted categorical variables for better analysis.
   - Checked for and removed outliers in key features like systolic (`ap_hi`) and diastolic (`ap_lo`) blood pressure.
   - Created new features such as BMI and transformed age from days to years.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized distributions of predictors like BMI, age, and blood pressure.
   - Analyzed categorical data (e.g., smoking, alcohol consumption, and physical activity).

3. **Data Modeling**:
   - Split the dataset into training (70%) and testing (30%) sets.
   - Implemented logistic regression, achieving an accuracy of **70.87%**.
   - Experimented with decision tree models, reaching an accuracy of **81.1%**.

4. **Results and Insights**:
   - Correlation analysis to identify relationships between predictors.
   - Model performance evaluation using metrics like accuracy and AIC.

---

## **Future Scope**
- **Advanced Classification**:
  - Support Vector Machines (SVMs)
  - Neural Networks
  - Multi-class classification for identifying specific cardiovascular conditions.
- **Device Integration**: Incorporate predictive models into wearable health devices.
- **Policy Development**: Utilize findings for public health awareness and policymaking.

---

## **Project Structure**

Project/ ├── cardio_train.csv # Dataset ├── MGT286A_Project_work.Rmd # R Markdown for analysis ├── MGT286A_Project_work.nb.html # HTML report generated from R Markdown ├── MGT286A Presentation.pptx # Project presentation ├── Project.Rproj # R project file ├── README.md # Project documentation

---

## **Install Required Libraries**
- **R**: `Tidyverse`, `ggplot2`, `caret`

To perform the analysis:
1. Install the required libraries in R.
2. Run the R Markdown file (`MGT286A_Project_work.Rmd`) to execute the analysis and generate reports.

---

## **Contributing**
Contributions are welcome! Please:
1. Fork the repository.
2. Make your changes.
3. Submit a pull request with a detailed explanation of your proposed changes.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.
