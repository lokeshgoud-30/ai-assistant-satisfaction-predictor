# AI Assistant Usage & Student Satisfaction Analysis

## 📁 Dataset
`ai_assistant_usage_student_life.csv`  
Contains 10,000 entries of student usage data with session details, tasks, satisfaction ratings, and outcomes.

## 🎯 Objective
To analyze student interaction with AI tools and predict their satisfaction level based on session data.

## 🧪 Methodology
- Cleaned and encoded dataset
- Exploratory data analysis with Seaborn & Matplotlib
- Created binary satisfaction label (Satisfied / Not Satisfied)
- Trained a Random Forest Classifier
- Evaluated performance using confusion matrix & classification report

## 🔍 Key Features Used
- Session length
- AI assistance level
- Task type
- Final outcome
- Discipline
- Reuse intent (`UsedAgain`)
- Student level (High School, Undergraduate)

## 📈 Results
- Accuracy: **77%**
- F1 Score: ~0.77
- Model shows balanced performance on both satisfied & unsatisfied classes

## 👨‍💻 Author
**Gounipalli Lokesh**

## 💡 Tools
- Python (pandas, seaborn, matplotlib, sklearn)
- VS Code (Jupyter Notebook interface)
