#  Customer Behaviour in Online Retail Transactions


** A comprehensive data analysis tool was designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists. The analytics tools employed here are quite straight forward.



## Dataset Content
* The dataset used for this analysis contains information on transactions made by customers through an online retail platform. The dataset includes data:
# Products purchased, 
# Quantity of each product,
# date and time of each transaction, 
# price of each product, 
# unique identifier for each customer who made a purchase, 
# country of purchase. 
This dataset was used to analyze customer behavior and preferences, identify popular products, and optimize pricing and marketing strategies.

## Business Requirements
To provide insights into customer behaviour, popular products, and pricing strategies to improve sales and marketing efforts. 
To achieve this by analysing online retail transaction data from the dataset sourced.

## Hypothesis and how to validate?


## Project Plan

1. Choosing the appropriate method to carry out the analysis from the start wwas important. I chose a method easy for me to understand and aslo to relay outcomes to the end user.
2. Loading data from the csv file downloaded from Kaggle onto a dataframe
3. Extracting and cleaning of the data by handling missing values,removing negative values from the quantity and price columns and also removing duplicates.
4. Tranforamation process involved creating a new column and adding it onto the dataframe .
5. Descriptive Analysis of the cleaned data to give us some correlations between the data cleaned. for example the RFM score.
6. The creation of visuals to further give insights into the exploratory analysis carried out.
7. Give a conclusion on what was derived from the analysis.

## The rationale to map the business requirements to the Data Visualisations

## Analysis techniques used
. Initial **RFM analysis** to give correlation.
. ****Descriptive statistics** **in form of a bar chart showing the top 10 products purchased according to revenue.
. Used a **Bar plot** to show the Customer Segmentation,;highlighting Best Customer vs Low Value Customer. 
. A ** **Heatmap** was used to further give insight into the frequency and recency relative to revenue.
. A **Boxplot** time series was also used for further insight.
. A** 3D Scatterplot** was used to show the country of purchase relation to customer behaviour. 


## Ethical considerations
The dataset used in this analysis was a public sourced dataset.

  

## Development Roadmap
The main challenge in had was creatingbthe 3d Scatter plot and trying to hover on it. Found it difficult to navigate on enlarging the scatterplot to give a better 3d view.



## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.
pandas: For data manipulation and analysis
numpy: For numerical computing
matplotlib: For creating static visualisations
seaborn: For statistical data visualisation
plotly : For creating 3d data visualisation

## Credits 
Data sourced from Kaggle and further credit with codes from the CI LMS.


## Acknowledgements (optional)
Thanks Vasi for your support and encouragement.
Mukti youare appreciated for yopur kind words and help getting started.