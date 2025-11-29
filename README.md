# Netflix-Recommendation-Engine
## 📌 Problem Statement
Recommendation engines play a crucial role in predicting user behavior and improving engagement by providing tailored suggestions. 
OTT platforms like Netflix and Amazon Prime Video rely on these engines to analyze user activity and recommend content based on preferences.
In this project, a movie recommendation engine is built from scratch to deliver personalized suggestions based on user interests and ratings.

## 🎯 Project Objective
To develop a personalized movie recommendation system that suggests movies to users by analyzing their interactions (ratings and preferences). 
The goal is to enhance user satisfaction by generating accurate and relevant recommendations.

## 🧾 Data Description
The project uses two key datasets:
movies.csv – Contains movie details such as movieId, title, and genres.
ratings.csv – Contains user ratings for movies with fields userId, movieId, and rating.
These datasets form the foundation for collaborative filtering and model training.

## ⚙️ Algorithm and Motivation
The project uses Collaborative Filtering with Singular Value Decomposition (SVD) to generate recommendations.
Why SVD?
It captures hidden relationships between users and movies.
Efficiently predicts missing ratings based on past interactions.
Widely used in production-grade recommendation systems (e.g., Netflix Prize model).

## 🧠 Assumptions
User ratings reflect their genuine preferences.
Movie genres in the dataset accurately represent their content.

## 📊 Model Evaluation
Data is split into training and testing sets using the train_test_split technique.
The SVD model is trained on the training set.
Root Mean Square Error (RMSE) is used to evaluate prediction accuracy.
User tastes remain relatively stable over time.

## 📈 Model Results & Key Findings
The SVD model successfully reduced the dimensionality of the user-item matrix to identify latent features. Final RMSE on Test Set: 0.5763. 
This demonstrates the model's high prediction accuracy, meaning the average prediction error is less than one whole star rating point.

## 🚀 Future Scope
Integrate user demographics, movie metadata, and contextual features (e.g., watch time, device used).
Implement a hybrid recommendation system combining content-based and collaborative filtering.
Deploy the model via a web app or API for real-time recommendations.

## 🧾 References
Kaggle Datasets,

YouTube Tutorials,

GitHub Repositories,

Medium Articles and Blogs

## 👩‍💻 Author
**Rashmi Sharma**  
📧 [Mail ID](mailto:rashusharma007@gmail.com)

🔗 [LinkedIn Profile](https://www.linkedin.com/in/rashmi-sharma-11nv91)
