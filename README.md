Student Performance Analysis System (Synthetic Data)
A Python-based analytics project that generates synthetic student academic data and applies data preprocessing, exploratory data analysis (EDA), and performance evaluation to uncover trends and insights in student performance.

Overview
This project simulates a real-world educational dataset for 250 students and runs a structured analytics pipeline to identify performance patterns, top performers, and at-risk students.
The workflow includes:

Synthetic data generation for 250 students
Data preprocessing and cleaning
Exploratory data analysis (EDA)
Performance evaluation and grade classification
Group-based and relational analysis
Visualization of trends and patterns


Note: All data is synthetically generated and does not represent any real student or institution.


Dataset
Source: Synthetic (generated programmatically)
ColumnDescriptionStudent_IDUnique student identifierNameStudent nameGenderMale / FemaleDepartmentCSE, IT, ECEYear1st / 2nd / 3rd yearMathsMarks in MathematicsScienceMarks in ScienceEnglishMarks in EnglishAttendance (%)Attendance percentage (50–100)Internal MarksContinuous assessment score (0–25)

Objectives

Generate a realistic synthetic dataset representing student academic records
Perform data cleaning and preprocessing
Analyze student performance using statistical methods
Identify top-performing and low-performing students
Perform group-based and relational analysis
Visualize key insights for better decision-making


Project Highlights
1. Data Generation

Created a synthetic dataset of 250 students
Included academic scores, attendance, and demographic attributes
Simulated real-world variability in student performance

2. Data Preprocessing

Checked for missing values and inconsistencies
Ensured correct data types for all columns
Prepared dataset for downstream analysis

3. Exploratory Data Analysis (EDA)
Used descriptive statistics including mean, median, mode, and standard deviation.
Computed derived columns:

Total marks
Average marks
Grade classification

4. Performance Analysis

Identified top-performing and low-performing (fail) students
Group-based analysis:

Department-wise performance
Gender-wise comparison
Year-wise trends



5. Relationship Analysis

Attendance vs. Marks
Internal Marks vs. Final Performance

6. Visualization
Chart TypePurposeBar ChartDepartment & gender analysisPie ChartDistribution overviewHistogramMarks distribution per subjectScatter PlotAttendance and internal marks relationships

Tools and Technologies
ToolPurposePythonCore programming languagepandasData manipulationnumpyNumerical computationsmatplotlibStatic visualizationsseabornStatistical visualizationsJupyter NotebookInteractive exploration

Requirements
bashpip install pandas numpy matplotlib seaborn faker

How to Run
Run as a Script
bashpython main.py
Run as a Notebook
Open the .ipynb file in Jupyter Notebook or Google Colab to explore data generation, EDA, and visualizations step by step.

Key Findings

Students with higher attendance tend to score better across all subjects
Internal marks positively influence final performance outcomes
Certain departments show consistently higher average scores
Clear distinction exists between top performers and at-risk students


Interpretation

Attendance plays a crucial role in academic success
Continuous assessment (internal marks) improves final outcomes
Group-based analysis helps institutions identify performance gaps
Visualization improves understanding of complex performance patterns


Future Improvements

Add a machine learning model for performance prediction
Build an interactive dashboard using Power BI or Streamlit
Integrate real-world datasets from educational institutions
Automate PDF/Excel reporting system
Add a student recommendation and intervention system


Project Structure
main.py                        # Main analysis script
notebook.ipynb                 # Jupyter Notebook for interactive exploration
README.md                      # Project documentation
