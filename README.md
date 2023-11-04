# NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING

**OBJECTIVE**
The objective of this project is to analyze and cluster a dataset related to Netflix. The dataset consists of various attributes associated with Netflix shows and movies, such as title, genre, release year, duration, rating, and others. The aim is to explore patterns and similarities among the content available on the platform and group them into meaningful clusters.

**DATASET**
This dataset contains information about various TV shows and movies available on Netflix, including details like the production country, release year, rating, duration, genre, and a description of each title. It consists of 12 columns and 7787 rows.

**VARIABLE DESCRIPTION**
- **show_id**: Unique ID for every Movie / TV Show
- **type**: Identifier - A Movie or TV Show
- **title**: Title of the Movie / TV Show
- **director**: Director of the Movie
- **cast**: Actors involved in the movie / show
- **country**: Country where the movie / show was produced
- **date_added**: Date it was added on Netflix
- **release_year**: Actual Release year of the movie / show
- **rating**: TV Rating of the movie / show
- **duration**: Total Duration - in minutes or number of seasons
- **listed_in**: Genre
- **description**: The Summary description

**CORE OF THE PROJECT**
To start, the dataset will be preprocessed by handling missing values, removing irrelevant columns, and transforming categorical variables into numerical representations.

Next, exploratory data analysis (EDA) techniques will be utilized to gain insights into the dataset. Visualizations and statistical summaries will be used to understand the distribution of variables, identify trends, and explore relationships between different features.

Additionally, to address the challenge of high dimensionality, we employ Principal Component Analysis (PCA) to reduce the number of components to 5654, capturing over 95% of the variance.

Once the dataset has been thoroughly analyzed, clustering algorithms such as k-means, hierarchical clustering. These algorithms will group similar Netflix shows and movies together based on their attributes. The optimal number of clusters will be determined using techniques like the elbow method or silhouette analysis.

After the clustering process, the results will be evaluated and interpreted. The clusters will be analyzed to understand the common characteristics and patterns within each group. This analysis will provide valuable information for Netflix in terms of content categorization, recommendation systems, and content acquisition strategies.

Finally, the findings and insights from the clustering analysis will be summarized and presented in a clear and concise manner. Visualizations, charts, and graphs will be used to effectively communicate the outcomes of the project. Recommendations may also be provided based on the identified clusters, suggesting potential improvements or strategies for Netflix to enhance user experience and content offerings.

**CONCLUSION**
In conclusion, this project aims to analyze a Netflix dataset, perform clustering techniques to group similar shows and movies together, and provide insights and recommendations based on the clustering results. The project will contribute to a better understanding of Netflix's content landscape and aid in decision-making processes for the company.

At the end, we can conclude that:
1. It is interesting to note that the majority of the content available on Netflix consists of movies.
2. Most of these shows are released either at the end or the beginning of the year.
3. The United States and India are among the top five countries that produce all of the available content on the platform. Additionally, out of the top ten actors with the maximum content, six of them are from India.
4. When it comes to content ratings, TV-MA tops the charts, indicating that mature content is more popular on Netflix.
5. The value of k=5 was found to be optimal for clustering the data.
6. Using this data, a Content-based recommender system was created using cosine similarity, which provided recommendations for Movies and TV shows.

**FUTURE WORK**
Integrating this dataset with external sources such as IMDB ratings and books clustering can lead to numerous intriguing discoveries. By incorporating additional data, a more comprehensive recommender system could be developed, offering enhanced recommendations to users. This system could then be deployed on the web for widespread usage.
