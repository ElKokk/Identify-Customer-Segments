
Project Overview

In this project, you will work with real-life data provided to us by our Bertelsmann partners AZ Direct and Arvato Finance Solution. 
The data here concerns a company that performs mail-order sales in Germany. 
Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. 
Your job as a data scientist will be to use unsupervised learning techniques to organize the general population into clusters, 
then use those clusters to see which of them comprise the main user base for the company. 
Prior to applying the machine learning methods, you will also need to assess and clean the data in order to convert the data into a usable form.


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