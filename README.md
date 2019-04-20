# Identify customer segments with Arvato

In this project, I worked with real-life data provided by Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. 

I used unsupervised learning techniques to organize the general population into clusters, then used those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, I also assessed and cleaned the data in order to convert the data into a usable form.



# Installation

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

# File Descriptions

**Identify_Customer_Segments.ipynb**

Jupyter Notebook divided into sections for completing the project. The notebook provides more details than the outline given here.


### Data
There are four files associated with the data of this project:
- `Udacity_AZDIAS_Subset.csv`: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- `Udacity_CUSTOMERS_Subset.csv`: Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- `Data_Dictionary.md`: Information file about the features in the provided datasets.
- `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographic data.

Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. We use this information to cluster the general population into groups with similar demographic properties. Then, we see how the people in the customers dataset fit into those created clusters. The hope here is that certain clusters are over-represented in the customers data, as compared to the general population; those over-represented clusters will be assumed to be part of the core userbase. This information can then be used for further applications, such as targeting for a marketing campaign.




# Licence
Feel free to use the code and let me know if the model can be improved. If you would like to do further analysis, it is available below under a [Creative Commons CC0 1.0 Universal (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/) license.
 
