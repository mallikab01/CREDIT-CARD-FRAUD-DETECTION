📌 Project Description : 
This project uses a Random Forest Classifier to detect fraud in credit card transactions. The dataset contains anonymized transaction details. The model identifies key features contributing to fraud detection and evaluates feature importance using MeanDecreaseAccuracy and MeanDecreaseGini.

📁 Dataset : 
credit.csv (anonymized features: V1-V28,Time,Amount,and Class)
Target variable: Class (0 = genuine, 1 = fraud)

⚙️ Project Steps
1. Data Preprocessing
   - Loaded dataset
   - Checked for class imbalance
   - Scaled features 
2. Model Building
   - Trained a Random Forest model
   - Split data into training and testing sets
   - Evaluated model performance (Accuracy, Precision, Recall)
3. Feature Importance
   - Visualized using MeanDecreaseAccuracy & MeanDecreaseGini
   - Most important features: Time, V3, V1, V5
4. Evaluation
   - Plotted confusion matrix and feature importance graph
   - Observed model’s strong ability to detect fraud
     
📊 Output
Output image is attached in the file
