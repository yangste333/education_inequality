# Education Inequality

# Authors
Stephen Yang

# Description
This project's goal is to determine if socioeconomic factors potentially have a bearing on school performance.

# Requirements
All analysis was done using Jupyter Notebook through Google Colab.

# Data
School ACT and SAT data was collected from Edgap.org. Some information from schools was also gathered from the National Center for Education Statistics.

A more accessable version of the NCES data can be accessed here: https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0

## Data Preparation
The taken data was joined together, and unreasonable and irrelevant data were taken out. The data was also split into training and testing sets, and a variable was computed to help with analysis.

The file data_prep/Education_Inequality_Data_Preparation.ipynb was used to complete the Data Preparation. The training data is under data_prep/educ_ineq_training.csv and the testing data is under educ_ineq_testing.csv.

## Analysis
Using the training and testing datasets, a good regression model using the primary numerical factors was made, and compared to a model factoring in region to see if factoring in region would improve the model significantly. Three main factors were found to be relevant, but factoring in region didn't seem to improve the model significantly.

The file Education_Analysis.ipynb was used to complete the Data Analysis.

# License
All datasets in this repository, including cleaned datasets, are free to use. All notebooks in this repository are also free to view and modify.
