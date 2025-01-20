#  Customer Behaviour in Online Retail Transactions


 A comprehensive data analysis tool was designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists. The analytics tools employed here are quite straight forward.



# Dataset Content
 The dataset used for this analysis contains information on transactions made by customers through an online retail platform. The dataset includes data:
## products purchased, 
## quantity of each product,
## date and time of each transaction, 
## price of each product, 
## unique identifier for each customer who made a purchase, 
## country of purchase. 
This dataset was used to analyze customer behavior and preferences, identify popular products, and optimize pricing and marketing strategies.

# Business Requirements
To provide insights into customer behaviour, popular products, and pricing strategies to improve sales and marketing efforts. 
To achieve this by analysing online retail transaction data from the dataset sourced.

# Hypothesis and how to validate?
To identify the frequently bought products by creating a new column for the Revenue. The use to plot a barchart.
To identify high spenders and frequent buyers using the customer segmentation created with the bar plot and pie chart.
To identify spending habit by country using bthe merged dataframe.

# Project Plan

1. Choosing the appropriate method to carry out the analysis from the start wwas important. I chose a method easy for me to understand and aslo to relay outcomes to the end user.
2. Loading data from the csv file downloaded from Kaggle onto a dataframe
3. Extracting and cleaning of the data by handling missing values,removing negative values from the quantity and price columns and also removing duplicates.
4. Tranforamation process involved creating a new column and adding it onto the dataframe .
5. Descriptive Analysis of the cleaned data to give us some correlations between the data cleaned. for example the RFM score.
6. The creation of visuals to further give insights into the exploratory analysis carried out.
7. Give a conclusion on what was derived from the analysis.

# The rationale to map the business requirements to the Data Visualisations
 A barchart to show the Top products sold. This gives a straight forward insight into the most purchased products.
 A barplot or pie chart show the customer distribution, very simple insight into who the loyal buyers are.
 A heatmap is important in showingn the RFM analysis carried out

# Analysis techniques used
. Initial **RFM analysis** to give relation between recency,frequency and revenue(monetary)

. **Descriptive statistics** in form of a bar chart showing the top 10 products purchased according to revenue.

. Used a **Bar plot** to show the Customer Segmentation,;highlighting Best Customer vs Low Value Customer. A **pie chart** was also used for this giving ban easier understanding to nthe customer distribution.

. A **Heatmap** was used to further give insight into the frequency and recency relative to revenue.

. A **Boxplot** time series was also used for further insight.

. A **3D Scatterplot** was used to show the country of purchase in relation to customer behaviour. 

# Conclusion

From the analysis carried out on the above dataset the following was derived:

1.*The Customer Segmentation* gave insight to the best customers (**High R, High F, High M)**.
These are customers who purchase frequently, spend the most, and have purchased recently.
They represent the most valuable customers and should be prioritized for retention and loyalty programs.
While at-risk customers **(Low R, Low F, High M**);are customers who used to spend a lot but haven't purchased recently. They are to be
considered for re-engagement campaigns like discounts or personalized offers to win them back.

2. Analysis showed which segments contribute the most to overall revenue:
Typically, Best Customers and Loyal Customers account for the majority of revenue.
This can help allocate resources effectively.

3.The boxplot helped to show the recency distribution. It shows which segments tend to have customers who shop more recently.
If there are high-recency segments,the focus will be on maintaining engagement with them.

4. The countries which have higher concentrations of valuable customers (e.g., customers with high Frequency or Monetary scores) was highlighted.This will help in targeting country-specific marketing campaigns.

By tailoring strategies to each segment, you can optimize revenue and improve customer satisfaction.



 Ethical considerations
The dataset used in this analysis was a public sourced dataset.

  

 Development Roadmap
The main challenge in had was creatingbthe 3d Scatter plot and trying to hover on it. Found it difficult to navigate on enlarging the scatterplot to give a better 3d view.



 Main Data Analysis Libraries
pandas: For data manipulation and analysis
numpy: For numerical computing
matplotlib: For creating static visualisations
seaborn: For statistical data visualisation
plotly : For creating 3d data visualisation

 Credits 
Data sourced from Kaggle and further credit with codes from the CI LMS.


# Acknowledgements (optional)
Thanks Vasi for your support and encouragement.

Mukti you are appreciated for your kind words and help getting started.