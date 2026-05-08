Student Performance Analysis using Python & Data Visualization

A complete Data Analysis Project built using Python, Pandas, and Matplotlib to analyze student academic performance data from the UCI Machine Learning Repository.

This project demonstrates the complete Data Analytics Workflow:

Data Loading
Data Cleaning
Exploratory Data Analysis (EDA)
Statistical Analysis
Data Visualization
Insights & Conclusions
📌 Project Overview

The project analyzes the Student Performance Dataset containing information about students’:

Demographics
Family background
Study habits
Lifestyle
Academic grades

The main goal is to discover patterns and relationships that affect student performance.

🎯 Aim

To analyze student performance data and identify factors affecting final academic grades using Python-based data analysis techniques.

🚀 Features
Upload dataset from ZIP or Excel file
Data cleaning and preprocessing
Missing value detection
Duplicate checking
Statistical analysis
Correlation analysis
Visualizations using Matplotlib
Insightful conclusions
🛠 Technologies Used
Programming Language
Python 3
Libraries
pandas
matplotlib
nltk
zipfile
google.colab
📂 Project Structure
Student-Performance-Analysis/
│── student_analysis.ipynb
│── student-mat.csv
│── README.md
⚙️ Software Requirements
Python 3.x
Jupyter Notebook / Google Colab
VS Code / PyCharm (optional)
Install Required Libraries
pip install pandas matplotlib openpyxl
💻 Hardware Requirements
Component	Requirement
Processor	Intel i3 or above
RAM	Minimum 4GB
Storage	500MB Free Space
OS	Windows / Linux / macOS
📖 Dataset Information
Dataset Source

Student Performance Dataset from:

UCI Machine Learning Repository
Dataset Size
Rows: 395
Columns: 33
Key Attributes
Feature	Description
age	Student age
sex	Gender
studytime	Weekly study time
failures	Past class failures
absences	Number of absences
G1	First period grade
G2	Second period grade
G3	Final grade
🧹 Data Cleaning & Exploration

The dataset was cleaned and explored using:

Missing value detection
Duplicate removal
Data type inspection
Shape analysis
Results

✅ No missing values found
✅ No duplicate rows found
✅ Dataset is clean and ready for analysis

📊 Analysis Performed
1️⃣ Average Final Grade
df['G3'].mean()

Result: 10.42

2️⃣ High Scoring Students

Students with:

G3 > 15

Result: 40 students

3️⃣ Correlation Analysis

Correlation between:

Study Time
Final Grade (G3)
df['studytime'].corr(df['G3'])

Result: 0.097

This indicates a very weak positive correlation.

4️⃣ Gender-wise Performance

Average final grade by gender:

Gender	Average G3
Female	9.97
Male	10.91
📈 Visualizations
Histogram of Final Grades

Shows distribution of student final grades.

Scatter Plot

Displays relationship between:

Study Time
Final Grade
Bar Chart

Compares average final grades by gender.

📸 Sample Output
Average G3: 10.42
Count G3 > 15: 40
Correlation studytime vs G3: 0.097
🧠 Key Concepts Used
Technique	Purpose
Data Cleaning	Remove inconsistencies
EDA	Understand dataset
Correlation Analysis	Find relationships
Visualization	Graphical insights
Statistical Analysis	Performance measurement
▶️ How to Run the Project
Step 1: Clone Repository
git clone https://github.com/your-username/Student-Performance-Analysis.git
Step 2: Install Libraries
pip install pandas matplotlib openpyxl
Step 3: Run Notebook
jupyter notebook

Open:

student_analysis.ipynb
📋 Workflow
1. Load Dataset
Upload ZIP or Excel dataset
2. Clean Data
Check null values
Remove duplicates
3. Analyze Data
Calculate averages
Correlation analysis
Group analysis
4. Visualize Data
Histograms
Scatter plots
Bar charts
5. Generate Insights
Interpret analysis results
📚 Learning Outcomes

This project helps in understanding:

Data Analysis Workflow
Data Cleaning Techniques
Exploratory Data Analysis (EDA)
Correlation Analysis
Python Data Visualization
Real-world Dataset Handling
📈 Future Enhancements
Machine Learning prediction model
Dashboard using Streamlit
Interactive visualizations with Plotly
Student performance prediction
Feature importance analysis
Deep learning integration
📄 Conclusion
Dataset is clean and well-structured
Average student performance is moderate
Only a small number of students score exceptionally high
Study time has very little impact on final grades
Male students slightly outperform female students in this dataset
🤝 Contribution

Contributions are welcome.

Fork the repository
Create a new branch
Improve the project
Submit a Pull Request
📄 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Balaji Kumar DV

GitHub: BalajikumarDV GitHub
LinkedIn: Balaji Kumar DV LinkedIn
