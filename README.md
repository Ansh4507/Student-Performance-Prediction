# Student-Performance-Prediction
This project predicts the performance of the student on the basis of the given dataset. you can predict your maths score 
# Introduction
This is a modular Flask web application that provides a prediction endpoint for an ensemble of machine learning models. It takes input data from a web form and returns the predicted result.
The project also includes CI/CD using GitHub Actions for automated build, test, and deployment.
# ScreenShot of the output
![Screenshot 2023-11-07 011612](https://github.com/Mr-Khandelwal/Student-Performance-Prediction/assets/112819492/a4c9571a-fa93-4537-9472-ffcbbd90cee1)

# Dataset 
Data set is used form the kaggle : - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977

# Steps to Run 
1 . Clone the repository:
```
git clone https://github.com/Mr-Khandelwal/Student-Performance-Prediction.git
```
2. Install requirement Dependencies :
```
pip install -r requirements.txt
```
3. Run the python file
```
python app.py
```
4. Run your website on any Search Engine with port no. 1000
```
localhost:1000
```
## About
The application expects the following data fields in the web form:

gender: The gender of the student.
ethnicity: The race/ethnicity of the student. parental_level_of_education: The parental level of education.
lunch: The type of lunch the student has.
test_preparation_course: Whether the student completed a test preparation course.
reading_score: The score obtained in the reading test.
writing_score: The score obtained in the writing test.
math_score: The score obtained in the math test. (prediction target)
The response from the /predict endpoint will be displayed on the home page via PredictPipeline.

# Contributors

-[Ansh Mishra](https://github.com/Mr-Khandelwal)
- [Rhythm](https://github.com/Rhythm-Gubrani)
- [Prerna Badlani](https://github.com/prerna0208)
- [Riya Sumra](https://github.com/riyasumra)

