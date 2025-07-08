
<h1 align="center">🏦LOAN APPROVAL ANALYSIS</h1>

## 📌 Summary
This project analyzes a simulated loan sanction dataset to replicate scenarios often seen in real-world financial institutions. The dataset comprises details about applicants such as personal demographics and financial background, allowing for robust data analysis, preprocessing, visualization, and predictive modeling.

🎯 **Key Goals**:
- Explore and understand the dataset 📊  
- Clean, transform, and preprocess the data 🧹  
- Visualize trends and relationships between variables 📈  
- Identify patterns, trends, and potential insights.💡

---

## 📊 Dataset Overview
- 📂**Source**: Loan application test dataset (CSV format)
- 📈**Entries**: 368 records
- 🧩**Important Features**:
     - `ApplicantIncome`
     - `CoapplicantIncome`
     - `LoanAmount`
     - `Loan_Amount_Term`
     - `Gender`, `Married`, `Dependents`
     - `Education`, `Self_Employed`
     - `Credit_History`
     - `Property_Area`
     - `Loan_ID`
- 🔧**Challenges Addressed**:
     - Missing values in categorical and numerical columns
     - Inconsistent data formatting
     - Skewed distributions requiring normalization/outlier handling

---

## 🔍 Exploratory Data Analysis  
- 📌 Visualized relationships using `Seaborn` and `Matplotlib`
- 📈 Correlation heatmaps to analyze numeric variable influence
- 📉 Boxplots to detect outliers
- 🔁 Countplots to observe distribution across categories

---

## 💡 Key Insights
- Higher credit history increases chances of loan approval ✅
- Married, educated, and self-employedapplicants tend to apply more often 👨‍👩‍👧‍👦
- Most loans are approved for those with moderate income 💸 

---

## 🛠️ Tech Stack
- 🐍**Python**
- **Libraries**: 📊 `Pandas`, 🔢`NumPy`, 📉`Matplotlib and Seaborn`, 🟠`Scikit-learn`
- 💻**Google Colab** for interactive analysis

---

## 📈 Visualizations Preview
- ✅ Loan Status: Majority of loans are approved (Loan_Status = Y).
- 💍 Married Applicants: Slightly higher approval rate than unmarried ones.
- 🎓 Education: Graduates get approved more often than non-graduates.
- 💼 Self-Employment: Lower approval rate among self-employed applicants.
- 💰 Applicant Income: High income does not guarantee approval; outliers detected.
- 💳 Loan Amount: Most loan amounts are between ₹100K–₹200K.
- 🏠 Property Area: Semiurban applicants have the highest approval rates.
- 🔁 Credit History: Strongest predictor of loan approval — credit history = 1 leads to higher approval.
- 📈 Correlation Heatmap:
    - ApplicantIncome and LoanAmount show strong positive correlation.
    
    - Credit_History weakly correlated with other numerical features but highly predictive.
 
---
## 🛠️ Setup
📥 Clone the repository  

   git clone https://github.com/your-username/loan-approval-project.git

---

## 🤝 Contribution
We welcome all contributions! 🚀
Want to improve this project? Follow the steps below:

1. Fork this repository

2. Create a feature branch (`git checkout -b feature-name`)

3. Commit your changes (`git commit -m 'Add new feature'`)  

4. Push to the branch (`git push origin feature-name`)

5. Create a Pull Request 🔃

---

## 📜 License

This project is licensed under the **MIT License**.  

---

## 👩‍💻 About Me
👋 Hi, I'm Anjali Gagneja. Passionate about uncovering insights through data and real world business insights.


🔗 **Let's Connect:**
- GitHub : https://github.com/Anjaligagneja07
- LinkedIN :[Anjali Gagneja](https://www.linkedin.com/in/anjali-gagneja-a35239297/)

---

## 🌟 Show Your Support
If you like this project, don't forget to ⭐ star the repo and share your feedback!
