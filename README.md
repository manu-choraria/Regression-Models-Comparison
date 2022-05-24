# Regression-Models-Comparison
The Following Repository Demonstrates the Comparison of Linear Regression and Multiple Linear Regression efficiency by using the housing prediction dataset. It also consists of the visualization of datasets and correlations among attributes of the dataset.

# *Dataset*
We have used house prediction dataset for our analysis that consist of 31978 Rows and 20 Columns. The 20 columns consist of various attributes that plays an important factor for housing price. The attributes are as described below:

id               
bedrooms         
bathrooms        
sqft_living      
sqft_lot         
floors           
waterfront       
view             
condition        
grade            
sqft_above       
sqft_basement    
yr_built        
yr_renovated     
zipcode         
lat              
long             
sqft_living15    
sqft_lot15       
price            

# *Code Explanation*
The Python code is implemnted using the google colab. The Code consists of the various Python Models which are as stated below:

1. Pandas- To perform DataFrames Operations.
2. Numpy- To perform Array Operations.
3. Matplotlib- To perform Visualizations.
4. Seaborn- To plot subbplots.
5. sklearn.preprocessing- To perform Preprocessing i.e., handling missing values.
6. sklearn.metrics- To measure the accuracy.
7. sklearn.linear_model-To perform linear regression.
8. mpl_toolkits.mplot3d- To plot 3d scatter Plot.
9. math- To perform Square Root.

The Code displays the values of the dataset. Moreover, it display the top 5 and bottom 5 entries using head and tail respectively. The 5 point summary of dataset is also described using the describe() function. The number of missing values in each row and column are also displayed using isnull() function. The data distribution is described using the histogram subplots.

The linear regression and multiple linear regression are performed using the sklearn module and accuracy is calculated using the Root Mean Square error. Thereafter, the correlation among different attributes is displayed using the 3d scatter plot, spearman rank coeffcient, and corelation matrix.
