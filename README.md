# Personalized-Student-Recommendations
AI Engineering Assignment - Personalized Student Recommendations

📌 Project Overview
----

This project provides a Python-based solution to analyze quiz performance and offer personalized study recommendations. By processing quiz data from API endpoints, it identifies weak topics, tracks improvement trends, and suggests actionable strategies for students.

📊 Data Sources
----

The project utilizes two datasets:

Current Quiz Data - Details of the user's latest quiz submission, including responses and topic coverage.

Historical Quiz Data - Performance data from the last 5 quizzes, tracking accuracy, scores, and response patterns.

Data is retrieved from three API endpoints:

**Quiz Endpoint**: https://jsonkeeper.com/b/LLQT

**Quiz Submission Data**: https://api.jsonserve.com/rJvd7g

**Historical Quiz Data**: https://api.jsonserve.com/XgAgFJ

⚙️ Setup Instructions
----
1️⃣ Clone the Repository

git clone <your-github-repo-link>
cd <your-repo-name>


2️⃣ Install Required Dependencies

Ensure you have Python 3.8+ installed, then run:

pip install -r requirements.txt

3️⃣ Run the Script

python main.py

📈 Approach & Methodology
----

Data Retrieval - Fetch quiz data from APIs.

Data Processing - Extract scores, accuracy, and quiz durations.

Performance Analysis - Identify weak/strong topics, improvement trends, and speed vs. accuracy balance.

Personalized Recommendations - Generate study suggestions based on quiz performance.

Visualization - Create graphs for performance insights.

📊 Key Insights & Recommendations
-----

Weak areas are highlighted, suggesting easier quizzes and concept revision.

Improvement trends track accuracy over multiple attempts.

Personalized study plans recommend difficulty levels and topic focus.

⭐ Bonus Features
-----

✅ Student Persona Analysis - Categorizes users based on strengths and weaknesses.
✅ Probabilistic Model (Future Scope) - Predicts NEET rank using quiz data and historical performance.

📌 Submission Details
----

🔗 GitHub Repo: [https://github.com/Abhra-deep/Personalized-Student-Recommendations]
📸 Screenshots: Included in the visualizations/ folder.
🎥 Demo Video: [https://drive.google.com/file/d/1ICVCqWNPeb5mkTHr4Tn4_VmNoPgWcGX0/view?usp=sharing]

🚀 Future Improvements
----

Implement a machine learning model to predict NEET ranks.

Extend analysis to include peer comparisons and topic-wise learning suggestions.

💡 About

This project is developed as part of the AI Engineering Assignment to showcase data-driven recommendations for personalized learning. 🚀
