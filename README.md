# Elderly Cognitive Health Assessment: SQL-Based Population Analysis

## 📋 Project Overview
Comprehensive SQL database analysis of 1,200 community-dwelling elderly adults (ages 60-89) examining demographic, health, and lifestyle factors associated with cognitive health outcomes. This project demonstrates proficiency in SQL database management, healthcare data analysis, and actionable insight generation for clinical decision-making.

## 🎯 Business Problem
Healthcare organizations need to identify elderly populations at risk for cognitive decline to allocate resources effectively and design targeted intervention programs. This analysis provides evidence-based insights into which demographic and lifestyle factors are associated with cognitive health outcomes in aging populations.

## 🛠️ Tools & Technologies
- **Python**: Pandas, SQLite3, NumPy
- **SQL**: SQLite database with complex queries
- **Excel**: Multi-sheet reports with xlsxwriter
- **Jupyter Notebook**: Interactive analysis documentation

## 📊 Dataset
- **Source**: Community Elderly Cognitive Health Dataset (Kaggle)
- **Size**: 1,200 elderly patients
- **Variables**: 16 features including demographics, health metrics, lifestyle factors
- **Key Measures**: 
  - MMSE Score (cognitive function, 0-30)
  - GDS Score (depression, 0-15)
  - Physical Activity Score (0-10)
  - Sleep Quality Score (1-5)
  - Chronic Disease Count (0-7)

## 🔍 Analysis Approach

### SQL Queries Developed:
1. **Demographic Overview**: Population characteristics and baseline metrics
2. **Age Group Analysis**: Health outcomes across three age brackets (60-69, 70-79, 80-89)
3. **Education Impact**: Cognitive reserve effects across education levels
4. **Chronic Disease Burden**: Multimorbidity impact on cognitive and mental health
5. **Lifestyle Factors**: Combined effects of physical activity and sleep quality

### Key SQL Techniques:
- Complex CASE statements for categorical segmentation
- GROUP BY with multiple aggregations (AVG, COUNT, MIN, MAX)
- Cross-tabulation of multiple variables
- Subgroup analysis with conditional logic

## 📈 Key Findings

### Population Demographics
- 1,200 elderly patients, average age 75 years
- Balanced gender (52% male) and residence (52% urban) distribution
- 90% score below normal cognitive threshold (MMSE < 24)

### Critical Insights
1. **Education is Protective**: Higher education associated with +0.79 MMSE points
2. **Depression Peak at 70-79**: Middle-old age group shows highest depression (GDS: 5.36)
3. **Optimal Disease Management**: Patients with 1-2 chronic conditions show best cognitive performance (21.90), suggesting benefits of healthcare engagement
4. **Sleep Crisis**: 42% of elderly have poor sleep regardless of activity level
5. **Lifestyle Complexity**: Moderate activity with poor sleep shows surprisingly good cognitive outcomes (22.28)

### Clinical Recommendations
- **Target 70-79 age group** for mental health screening and support
- **Universal sleep interventions** needed across all patient segments
- **Cognitive screening programs** for low-education populations
- **Maintain healthcare engagement** for those with chronic conditions
- **Promote moderate physical activity** (4-6/10) as achievable goal

## 📁 Project Structure

## 📊 Deliverables
1. **SQLite Database**: Structured elderly health database with 1,200 records
2. **Excel Report**: 7-sheet workbook including:
   - Executive Summary
   - 5 Analysis Worksheets
   - SQL Query Documentation
3. **SQL Documentation**: Complete query library with business context
4. **Jupyter Notebook**: Reproducible analysis with markdown explanations

## 💡 Skills Demonstrated
- SQL database creation and management
- Complex query development (CASE, GROUP BY, aggregations)
- Healthcare data analysis and interpretation
- Clinical insight generation from population data
- Professional reporting and documentation
- Data storytelling for non-technical stakeholders

## 🔗 How to Use This Project
1. Download all files from this repository
2. Open `Analysis_Notebook.ipynb` in Jupyter Notebook
3. Run all cells to reproduce the analysis
4. Review `Elderly_Cognitive_Health_SQL_Analysis.xlsx` for formatted results
5. Reference `SQL_Queries_Documentation.txt` for query syntax

## 📝 Future Enhancements
- Power BI dashboard for interactive visualization
- Predictive modeling for cognitive decline risk
- Longitudinal analysis if follow-up data becomes available
- Integration with electronic health records (EHR) systems

## 👤 Author
Emmanuel Eugene 
Data Analyst | Emerging Aging Researcher  
emmanueleugene20@gmail.com

## 📅 Project Date
December 2025

*This project demonstrates practical application of SQL and data analysis skills to real-world healthcare challenges in geriatric population health management.*
