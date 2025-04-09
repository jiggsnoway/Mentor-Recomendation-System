🎯 Project Title
AI/ML-Based Mentor Recommendation System for CLAT Aspirants

📌 Objective
To build a simple machine learning-based recommendation system that suggests suitable mentors (CLAT toppers) to law aspirants based on their preferences, study habits, and target colleges.

🧠 Approach
Created mock data for 5 aspirants and 6 mentors using pandas.

Key features used:

Preferred subject
Target college
Preparation level
Learning style

Applied one-hot encoding using pd.get_dummies() to convert categorical features into numerical format.

Used cosine similarity to calculate the closeness between aspirant and mentor profiles.

For each aspirant, the system recommends the top 3 most similar mentors.

🧪 Tech Stack

1. Python

2. Google Colab

3. Pandas

4. NumPy

5. scikit-learn (cosine similarity)

💡 Bonus: Feedback-Based Improvement (Concept Only)
In a real-world application, the system can improve with feedback:

1. Collect mentor ratings from aspirants.

2. Use feedback to update mentor scores or build a collaborative filtering model.

3. Combine similarity with mentor rating to generate a weighted score.

4. Reduce the chance of recommending mentors who receive low feedback.

🚀 How to Run This Project
1. Open the .ipynb file in Google Colab.

2. Run the cells in order to generate mock data, preprocess it, and compute mentor recommendations.

3. The output shows the top 3 mentor matches for each aspirant based on their profile similarity.

