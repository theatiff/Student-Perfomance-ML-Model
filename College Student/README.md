# College Student Performance Prediction Using Machine Learning

## About the Project

This project uses Machine Learning to predict college students' grades based on their course information and questionnaire responses.

The project uses a dataset containing 145 student records and 30 questionnaire features.

## Technologies Used

* Python
* Google Colab
* Pandas
* Matplotlib
* Scikit-learn
* XGBoost
* Joblib

## Machine Learning Algorithms

We tested five machine learning algorithms:

1. Decision Tree
2. Random Forest
3. Logistic Regression
4. Support Vector Machine (SVM)
5. XGBoost

## Model Results

| Algorithm           | Average Cross-Validation Accuracy |
| ------------------- | --------------------------------: |
| Decision Tree       |                            31.72% |
| Random Forest       |                            35.86% |
| Logistic Regression |                            28.28% |
| SVM                 |                            29.66% |
| XGBoost             |                            35.17% |

Random Forest achieved the highest average cross-validation accuracy of 35.86%.

## Project Files

* `Higher_Data.ipynb`: Data analysis, preprocessing, model training and evaluation.
* `College_Student_Prediction.ipynb`: Predicts grades for new students.
* `higher data.csv`: College student dataset.
* `college_student_model.pkl`: Saved trained Random Forest model.

## How to Run

1. Open Google Colab.
2. Upload `College_Student_Prediction.ipynb`.
3. Upload `college_student_model.pkl` when requested.
4. Run the notebook cells.
5. Enter student information and view the predicted grade.

## Grade Categories

The dataset uses these original grade categories:

* 0: Fail
* 1: DD
* 2: DC
* 3: CC
* 4: CB
* 5: BB
* 6: BA
* 7: AA

## Project Limitation

The dataset contains only 145 records. The model's accuracy is limited, so its predictions should not be treated as final academic results.

## Author

M.Tech Artificial Intelligence and Machine Learning Student
