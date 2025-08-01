# Student Performance Prediction
This is a simple linear regression project I built using PyTorch to predict how well a student might perform based on things like how much they study, how many sample papers they solved, sleep hours, attendance, etc.

📊 Dataset
Used a CSV file with the following columns:

Hours Studied

Previous Scores

Attendance

Sleep Hours

Sample Question Papers Practiced

Target: Performance Index

🛠️ What I Did
Scaled the input features using StandardScaler

Split the data into training and test sets (75/25 split)

Built a linear regression model from scratch using PyTorch

Trained it using the Adam optimizer and MSELoss

Ran for 1000 epochs (maybe overkill, but why not 😄)

📈 Final Results
Train Loss: ~4.16

Test Loss: ~4.21

R² Score on Test Set: 0.9887 (Pretty solid!)
