# EWAirlines_clustering
This project involves clustering passengers from the EastWest Airlines frequent flyer program using an unsupervised learning approach (KMeans) to identify distinct customer segments for targeted .
<img src="https://github.com/rpjinu/EWAirlines_clustering/blob/main/EW.jpg" width=1000>


Project Steps:
1. Data Preprocessing
Load the dataset from the CSV file.
Drop unnecessary columns (e.g., ID) that do not contribute to clustering.
Check for and handle missing values appropriately.
Normalize the data to ensure all features contribute equally to the clustering process.
2. Clustering
Apply the KMeans clustering algorithm to identify clusters of passengers.
Determine the optimal number of clusters using methods like the elbow method or silhouette score.
3. Cluster Evaluation
Analyze the resulting clusters to understand passenger characteristics.
Document the insights gained from each cluster for better marketing strategies.
4. Model Training
Treat the identified clusters as labels for a supervised learning task.
Split the data into features and target variables.
Train a classification model (e.g., Random Forest) using the cluster labels as the target.
5. Model Saving and Loading
Save the trained model to a file for later use.
Implement functionality to load the saved model for making predictions.
6. Making Predictions
Use the saved model to predict cluster labels for new passenger data.
Provide insights based on the predicted clusters to tailor mileage offers.
Key Libraries Used:
pandas: For data manipulation.
scikit-learn: For clustering and classification.
joblib: For saving and loading the model.
Conclusion:
The project effectively identifies and analyzes clusters of passengers based on their flying behavior, enabling targeted marketing strategies to enhance customer satisfaction and loyalty.

