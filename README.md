📌 Project Overview This project is an Unsupervised Machine Learning task focused on clustering Netflix's vast library of movies and TV shows. By analyzing text-based features like descriptions, cast, and genres, the goal is to group similar content together to enhance recommendation strategies and understand global content trends.

🎯 Business Objectives

Improve User Retention: Enhance the foundation for recommendation engines.

Content Strategy: Understand the shift from movies to TV shows since 2010.

Regional Analysis: Identify content preferences in different countries like the US and India.

Market Insights: Target adult and teen demographics (TV-MA, TV-14) effectively.

🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, NLTK

Techniques: TF-IDF Vectorization, NLP (Natural Language Processing), K-Means Clustering, Principal Component Analysis (PCA)

📂 Dataset Description The dataset consists of TV shows and movies available on Netflix as of 2019, collected from Flixable.

Total Records: 7,787 rows

Total Features: 12 columns

Key Features: type, title, director, cast, country, rating, listed_in, description.

🚀 Project Workflow

Exploratory Data Analysis (EDA): Created over 15 logical charts to find deep insights.

Data Cleaning: Handled missing values (imputed 'Unknown' for Director/Cast) and treated outliers.

Text Pre-processing:

Lowercasing, Punctuation removal, Stopword removal.

Lemmatization to normalize text.

TF-IDF Vectorization to convert text into a 5,000-feature numerical matrix.

Clustering Implementation:

K-Means: Optimal clusters found using the Elbow Method and Silhouette Score.

Hierarchical Clustering: Visualized using a Dendrogram.

Deployment Ready: Saved the best-performing model using a pickle file.

📊 Key Findings

The "Binge" Era: TV shows have nearly tripled since 2010, while movie titles have decreased.

Global Hubs: United States and India are the largest contributors to the library.

Adult Focus: The majority of content is rated TV-MA, showing Netflix's focus on mature audiences.

📝 Conclusion The project successfully categorized Netflix content into 6 meaningful clusters. This automated clustering allows for better content discoverability and data-driven decision-making for future content acquisitions.
