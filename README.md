Predict AI: Revolutionizing Disease Prediction with Machine Learning

Problem Statement
Early disease detection is crucial for effective treatment and reducing mortality rates. However, traditional diagnostic methods are often time-consuming, expensive, and reliant on specialized
doctors—resources that are scarce in rural areas. Delayed or inaccurate diagnoses can lead to severe health complications and increased costs.

With the rise of chronic diseases like diabetes, heart disease, and cancer, there is a pressing need for faster and more affordable diagnostic solutions. AI and machine learning offer a promising 
approach to building intelligent tools that assist doctors in early and accurate disease prediction. By leveraging these technologies, we can improve healthcare accessibility, reduce diagnostic delays,
and enhance patient outcomes.

Solution Overview:
This project is a Disease Predictor that uses machine learning to predict diseases based on symptoms provided by the user. The system employs three different machine learning algorithms: Decision 
Tree, Random Forest, and Naive Bayes. The user inputs up to five symptoms, and the system predicts the most likely disease based on the trained models.

Technologies Used:
Python: The primary programming language used for the project.
Tkinter: A Python library used for creating the graphical user interface (GUI).
Pandas: Used for data manipulation and handling the dataset.
NumPy: Used for numerical computations.
Scikit-learn: A machine learning library used for implementing the Decision Tree, Random Forest, and Naive Bayes algorithms.
CSV Files: The dataset containing symptoms and corresponding diseases is stored in CSV files.

Setup & Installation:
Follow these steps to set up and run the project on your local machine:
1. Prerequisites
   Ensure you have Python installed (preferably Python 3.8 or higher).
   Install the required Python libraries using pip.

2. Install Required Libraries
  Open a terminal or command prompt and run the following commands:
  pip install numpy pandas scikit-learn tkinter

3. Download the Dataset
  1. The project uses two CSV files: 
      Training.csv
      Testing.csv
  2. Update the file paths in the code if not necessary:
     Line No. 50:
     df = pd.read_csv(r"C:\Users\LENOVO\OneDrive\Documents\Training.csv")
     Line No. 71:
     tr = pd.read_csv(r"C:\Users\LENOVO\OneDrive\Documents\ Training.csv")
     Line No. 351:
     tr=pd.read_csv(r" C:\Users\LENOVO\OneDrive\Documents\ Testing.csv")


 
4. Save it as disease_prediction.py
5. Run the Project: disease_prediction.py


Usage Instructions:
Once the application is running, follow these steps to interact with the prototype:
1. Enter Patient Information
•	In the GUI, enter the name of the patient in the "Name of the Patient" field.
2. Select Symptoms
•	Choose up to five symptoms from the dropdown menus:
o	Symptom 1
o	Symptom 2
o	Symptom 3
o	Symptom 4
o	Symptom 5
3. Predict Disease
•	Click one of the following buttons to predict the disease using the corresponding algorithm:
o	DecisionTree: Predicts the disease using the Decision Tree algorithm.
o	RandomForest: Predicts the disease using the Random Forest algorithm.
o	NaiveBayes: Predicts the disease using the Naive Bayes algorithm.
4. View Results
•	The predicted disease (or "Not Found") will be displayed in the corresponding text box below each button.
5. Reset or Try Again
•	To make a new prediction, simply select new symptoms and click the prediction buttons again.
