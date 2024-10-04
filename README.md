
# Healthcare Prediction on Diabetes Patients




## Overview
This project aims to predict the likelihood of diabetes in patients using machine learning models and provide an easy-to-use web interface built with Streamlit. 
The solution includes data analysis, model training, and a web interface for end users to input medical parameters and receive predictions.
## Features
1) Data Analysis: Detailed analysis of various parameters affecting diabetes.

2) Machine Learning Prediction: A trained model that predicts whether a person is diabetic or not based on input features like glucose levels, BMI, etc.

3) User-Friendly Web Interface: Built using Streamlit, allowing users to interact with the model without coding knowledge.

## Technologies Used
1) Python Libraries: Pandas, NumPy, Seaborn, Scikit-learn.

2) Model Used: The model is stored as diabetes_model.sav.

3) UI: Streamlit for a user-friendly interface.
## Project Structure
1) app.py: The main script for running the Streamlit web application.

2) db.ipynb: Jupyter Notebook that contains data analysis and model training code.

3) diabetes_model.sav: The trained model file used for predictions.

4) diabetes.csv: A csv file containing dataset of diabetes patients which was used for traning and analysis purpose.

## How to Use This Project
1) Clone the Repository:
git clone https://github.com/Rajkumar2002/healthcare-diabetes-prediction.git
cd healthcare-diabetes-prediction

2) Install Dependencies: Make sure you have Python installed (Python 3.8+ recommended). Install the necessary Python libraries using:
pip install -r requirements.txt

3) Run the Application: Run the Streamlit application using the command:
streamlit run app.py


## How It Works
1) Input Parameters: Users can enter medical details such as glucose level, BMI, blood pressure, and more.
2) Prediction: After submitting, the app uses the trained ML model (diabetes_model.sav) to predict whether the user is likely diabetic.
3) Output: The prediction will be displayed on the interface.

## Screenshots![Screenshot 2024-10-04 093432](https://github.com/user-attachments/assets/9876f802-2d91-4adb-ba83-aa39470731a9)

![Screenshot 2024-10-04 093503](https://github.com/user-attachments/assets/68ddc85c-5fcf-4fe3-ae16-a1018f4120c8)

OUTPUT
![Screenshot 2024-10-04 094826](https://github.com/user-attachments/assets/dc09077d-aa7a-4069-a8b5-6d0cc416e850)

![Screenshot 2024-10-04 094835](https://github.com/user-attachments/assets/1a2fb35d-b236-4599-a8eb-2e9eee5a276c)



## Contributing

Contributions are always welcome!

 If you want to make any improvements or add new features, feel free to open an issue or submit a pull request.
 
Please adhere to this project's `code of conduct`.


## Contact
For any questions or feedback, please reach out to rajkumarnainala08@gmail.com.
