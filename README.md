# Netflix Movie Recommendation System

A Netflix Movie Recommendation System built using Apriori and ECLAT Association Rule Mining. The project analyzes movie-viewing patterns to discover frequent itemsets and generate recommendations based on strong associations.

# 🚀 Features

Movie recommendation using association rules
Apriori algorithm implementation
ECLAT algorithm implementation
Frequent itemset mining
Support, Confidence, and Lift analysis
Comparison of Apriori and ECLAT results
🛠️ Tech Stack
Python
Pandas
NumPy
MLxtend
Matplotlib
Seaborn
Jupyter Notebook

 # ⚙️ Workflow
flowchart TD
    A[Netflix Movie Dataset] --> B[Data Cleaning & Preprocessing]
    B --> C[Create User-Movie Transactions]
    C --> D[Generate Transaction Matrix]

    D --> E[Apriori Algorithm]
    D --> F[ECLAT Algorithm]

    E --> G[Frequent Itemsets]
    F --> G

    G --> H[Generate Association Rules]
    H --> I[Calculate Support, Confidence & Lift]
    I --> J[Filter Strong Rules]
    J --> K[Generate Movie Recommendations]


# 📊 Evaluation

The recommendation rules are evaluated using:

Support – How frequently movies occur together
Confidence – Probability of recommending one movie based on another
Lift – Strength of the association between movies
# 🎯 Objective

The goal of this project is to demonstrate how association rule learning can be applied to build a movie recommendation system and explore the differences between Apriori and ECLAT algorithms.

# 👨‍💻 Author

Neeraj Yadav
B.Tech Computer Science Engineering | Python & Machine Learning Enthusiast
