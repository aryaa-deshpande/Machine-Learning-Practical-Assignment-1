# **Machine Learning Practical Assessment 1**

This project contains two parts — **Regression** and **Binary Classification** — based on the **UCI Student Performance Dataset**.  
Both sections explore how various factors influence student outcomes.

---

## **Part 1: Regression**

In this part, I built a linear regression model to predict students’ final grades (**G3**) using different academic and social factors.  
The first two term grades (**G1** and **G2**) were excluded to make the prediction more realistic.

The model achieved an **R^2 of 0.091** with an **RMSE of 3.75**.  
Results show that past failures have the strongest negative effect on performance, while socializing (`goout`) slightly lowers grades.  
Both Mother’s and Father's educations have a clear positive influence, and students from urban areas score a little higher on average than those from rural areas.

- `regression/Regression_Code.ipynb` – contains the full code with EDA, model training, and evaluation steps.  
- `regression/Regression_Report.pdf` – includes the written answers and short explanations for each question.

---

## **Part 2: Binary Classification**

In this part, I built a simple logistic regression model to predict whether a student would pass or fail based on their final grade (**G3**).  
Any grade above 15 counts as a pass, and 15 or below as a fail.

The model performed quite well with an accuracy of about **89%** and an AUC score of **0.73**.  
Students with more absences were slightly less likely to pass, and those with more educated mothers tended to do better overall.

- `classification/Classification_Code.ipynb` – contains all the code and short markdown notes.  
- `classification/Classification_Report.pdf` – includes the written answers and reasoning for each question.

---

## **Summary**

The goal of this project was to use basic machine learning methods to analyze patterns in student performance.  
Linear Regression was used to study grade outcomes, and Logistic Regression was used to classify students as pass or fail.  
The notebooks are simple, well-documented, and show how small datasets can be used for meaningful insights.