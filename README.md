
Project Overview

In this project, I will apply unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. 
These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. 
The data that I will use has been provided by at Bertelsmann Arvato Analytics, and represents a real-life data science task.

Our Data

There are four files associated with this project

- `Udacity_AZDIAS_Subset.csv`: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- `Udacity_CUSTOMERS_Subset.csv`: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- `Data_Dictionary.md`: Detailed information file about the features in the provided datasets.
- `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns

Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. You will use this information to cluster the general population into groups with similar demographic properties. Then, you will see how the people in the customers dataset fit into those created clusters. The hope here is that certain clusters are over-represented in the customers data, as compared to the general population; those over-represented clusters will be assumed to be part of the core userbase. This information can then be used for further applications, such as targeting for a marketing campaign.



Why this project?

The unsupervised learning branch of machine learning is key in the organization of large and complex datasets. 
While unsupervised learning lies in contrast to supervised learning in the fact that unsupervised learning lacks objective output classes or values, 
it can still be important in converting the data into a form that can be used in a supervised learning task. 
Dimensionality reduction techniques can help surface the main signals and associations in your data, providing supervised learning techniques a more focused set of features 
upon which to apply their work. 
Clustering techniques are useful for understanding how the data points themselves are organized. These clusters might themselves be a useful feature in a directed supervised learning task. This project will give you hands-on experience with a real-life task that makes use of these techniques, focusing on the unsupervised work that goes into understanding a dataset.

In addition, the dataset presented in this project requires a number of assessment and cleaning steps before you can apply your machine learning methods. 
In workplace contexts, you will frequently need to work with data that is untidy or needs preprocessing before standard algorithms and models can be applied. 
The ability to perform data wrangling and the ability to make decisions on data that you work with are both valuable skills that you will practice in this project.