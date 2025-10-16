# Parkinsons-Classification-Model
After learning that one of my favorite actors, Michael J. Fox, was diagnosed with Parkinson’s Disease, I felt inspired to build something—however small—that could contribute to understanding 
or helping those affected by this condition.


Parkinson’s Disease is a progressive nervous system disorder that affects movement, leading to shaking, stiffness, and difficulties with walking, balance, and coordination.
Its symptoms usually begin gradually and worsen over time. This project uses data from the Oxford Parkinson’s Disease Detection Dataset to build a machine learning model capable of predicting 
whether a person is likely to have Parkinson’s based on biomedical voice measurements.

Dataset

The dataset consists of biomedical voice measurements collected from 31 individuals—23 diagnosed with Parkinson’s and 8 healthy controls.
The model analyzes variations in voice frequency and classifies them as:

0 → Healthy
1 → Parkinson’s Disease

Project Workflow
1)Imported the necessary Python libraries.
2)Explored the dataset using basic descriptive statistics and visualization.
3)Examined the distribution of samples between healthy and affected individuals.
4)Selected relevant features and separated the target column (status).
5)Split the data into training (80%) and testing (20%) sets.
6)Standardized the data to improve model performance.
7)Trained a Support Vector Machine (SVM) classifier.
8)Evaluated the model’s accuracy and reliability on test data.
9)Built a predictive system that can classify new data as healthy or Parkinson’s.

Results and Learning
This project taught me how to handle data from start to finish: cleaning, exploring, training, and evaluating a predictive model.
More importantly, it helped me understand how data science can intersect with healthcare, reinforcing my interest in using technology for meaningful impact.
I plan to further develop and refine this model in the future.

Technologies Used
Python
NumPy
Pandas
Scikit-learn

Matplotlib / Seaborn
