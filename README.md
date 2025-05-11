# Student-Performance-Analysis-Report
Student Performance Analysis
![Dashboard 2](https://github.com/user-attachments/assets/8d8a29a2-92b8-4462-9241-8a836890eafd)

📊 Overview
This project investigates the relationships between student performance and various demographic and academic factors. By analyzing test scores across different subject areas and their correlations with socioeconomic indicators, we aim to identify key factors influencing academic achievement and provide actionable recommendations for educators and policymakers.
🎯 Key Objectives

Identify significant correlations between student performance and demographic/socioeconomic factors
Examine the impact of parental education level, economic status, and test preparation on academic outcomes
Analyze gender-based performance differences across subject areas
Provide evidence-based recommendations for targeted educational interventions

📋 Dataset
The analysis utilizes a dataset containing information on 1,000 students, including:
Independent Variables:

Gender
Race/ethnicity
Parental level of education
Lunch type (as a socioeconomic indicator)
Test preparation course completion

Dependent Variables:

Math score
Reading score
Writing score
Aggregate score (calculated as the average of math, reading, and writing scores)

📈 Key Findings
Gender-Based Performance Differences
Our analysis revealed significant gender-based disparities in subject performance:
SubjectMale AverageFemale AverageDifferenceMath68.73%63.63%+5.10% (M)Reading65.47%72.61%+7.14% (F)Writing63.31%72.47%+9.16% (F)
Impact of Socioeconomic Factors

Parental Education: Students whose parents completed higher education consistently achieved better scores across all subjects
Economic Status: Students receiving standard lunch scored 104.52% higher on average than those with free/reduced lunch
Test Preparation: Students who completed test preparation courses outperformed non-participants by 7.23% across subjects

Installation

Clone this repository:
bashgit clone https://github.com/yourusername/student-performance-analysis.git
cd student-performance-analysis

Create a virtual environment and install dependencies:
bashpython -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

Run the Jupyter notebook:
bashjupyter notebook notebooks/student_performance_analysis.ipynb


📊 Visualizations
Gender Performance Across Subjects
Show Image
Parental Education Impact
Show Image
Economic Status Effect
Show Image
Test Preparation Impact
Show Image
📝 Recommendations
Based on our findings, we recommend:

Gender-Specific Interventions: Targeted math support for female students and reading/writing enhancement for male students
Socioeconomic Support: Expanded access to educational resources for disadvantaged students
Nutritional Programs: Expanded free/subsidized lunch programs
Test Preparation Integration: Incorporation of test preparation strategies into standard curricula
Comprehensive Support: Personalized learning plans based on individual student needs

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
🤝 Acknowledgements

Dataset obtained from Kaggle
Inspired by educational research on socioeconomic factors in student performance
