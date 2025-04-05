📊 Netflix Movies & TV Shows Clustering (Unsupervised Learning)


📌 Project Overview
With thousands of titles in Netflix’s catalog, manually organizing and analyzing content becomes challenging. This project uses unsupervised learning to cluster similar movies and TV shows based on various features. The insights can support better content recommendations, tagging, and strategic planning.

🎯 Objective
Cluster similar movies and TV shows using features like genre, release year, and duration.

Apply unsupervised learning techniques to discover hidden content patterns.

Create visual insights into how Netflix's content is distributed and grouped.

🧰 Tools & Technologies
Python: Numpy, Pandas, Scikit-learn

Visualization: Matplotlib, Seaborn

Machine Learning: K-Means Clustering, PCA (Principal Component Analysis)

📄 About the Dataset
The dataset contains metadata about Netflix content, including:

Show type (Movie/TV Show)

Title, Genre, Cast

Country of production

Release year

Duration

🧹 Data Preprocessing
Cleaned missing or inconsistent entries (e.g., standardized duration formats)

Converted categorical data into numerical form using encoding techniques

Applied PCA to reduce data dimensions and improve clustering performance

🔍 Actionable Insights
Content Grouping: Content was segmented into meaningful clusters

Genre Overlap: Identified dominant genres in overlapping categories

Temporal Trends: Older shows clustered differently than newer ones

Content Diversity: Highlighted regional content similarities

Movie vs TV Patterns: Clear separation between movies and TV shows

📈 Key Results
Used the Elbow Method to determine the optimal number of clusters

Applied K-Means Clustering to group content

Used PCA to visualize data in 2D for easier interpretation

Gained a better understanding of how Netflix’s content is structured

💼 Business Impact
For Netflix:

Improved recommendation systems through automatic content grouping

Helped content strategists identify gaps and patterns in releases

For Data Teams:

Enhanced tagging systems using machine-generated clusters

Enabled more informed, data-driven decisions in content acquisition

📊 Sample Visualizations
(You can add image links or screenshots of your cluster plots, PCA visuals, etc.)

🚀 How to Run
Clone the repo

Install required packages (pip install -r requirements.txt)

Run the Jupyter notebook or Python script

Explore the visualizations and insights
