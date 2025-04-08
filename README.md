📊 Netflix Movies & TV Shows Clustering (Unsupervised Learning)
Unsupervised machine learning is used in this project to cluster Netflix content based on features like genre, release year, and duration — helping uncover hidden patterns and supporting better recommendations and strategic decisions.


![netflix](https://github.com/user-attachments/assets/4c7e126e-4653-4e04-80b2-74792402899e)

📌 Project Overview
With thousands of titles in Netflix’s ever-expanding catalog, manually organizing and understanding content becomes difficult. This project tackles that challenge using clustering techniques.

Goals:

🔍 Cluster similar movies and TV shows

🧠 Discover hidden patterns in content using unsupervised learning

📈 Create visual insights into Netflix's content distribution

🧰 Tools & Technologies
Programming Language & Libraries

🐍 Python: NumPy, Pandas, Scikit-learn

📊 Visualization: Matplotlib, Seaborn

🧪 Machine Learning: K-Means Clustering, PCA (Principal Component Analysis)

📄 About the Dataset
The dataset includes metadata for Netflix titles, with columns such as:

Feature	Description
type	Type of content (Movie/TV Show)
title	Name of the show
listed_in	Genre(s)
cast	Cast members
country	Country of production
release_year	Year released
duration	Runtime (in minutes or seasons)
🧹 Data Preprocessing
Key steps before clustering:

✅ Cleaned missing or inconsistent values (e.g., duration format)
![netflix 1](https://github.com/user-attachments/assets/89d74dc5-6daf-47ce-826f-29121954ed21)

🔁 Converted categorical data into numerical format via encoding

🔻 Applied PCA to reduce dimensionality and enhance clustering performance

🔍 Actionable Insights
🧩 Content Grouping: Similar types of content were naturally grouped
🎭 Genre Overlap: Discovered hybrid genres and dominant categories
🗓️ Temporal Trends: Older vs. newer content clustered distinctly
🌍 Content Diversity: Regional similarities emerged in clusters
📺 Movie vs TV Show: Clear visual separation between formats

📈 Key Results
📉 Used the Elbow Method to determine the ideal number of clusters

🔁 Applied K-Means Clustering for grouping

🔻 Used PCA for 2D visualization of high-dimensional features

🔍 Revealed insightful structure in Netflix’s content catalog

💼 Business Impact
For Netflix:
🔁 Better recommendation engine through auto-grouping

🧠 Strategic content planning based on grouped clusters

📚 Efficient tagging systems with machine-detected similarities

For Data Teams:
🧪 Enhanced understanding of content layout and user consumption

🎯 Data-driven decisions in content acquisition and curation

📊 Sample Visualizations
Add your cluster plots and PCA visualizations here.

🎯 PCA Visualization

📌 Content Clusters

🚀 How to Run
bash
Copy
Edit
# Clone the repository
git clone https://github.com/your-username/netflix-clustering.git
cd netflix-clustering

# Install required packages
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook Netflix_Clustering.ipynb

🙋‍♂️ Contact
prince pareek
📧 princepareek29@gmail.com
