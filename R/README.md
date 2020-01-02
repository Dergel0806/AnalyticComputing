### Employee_compensation_data_analysis

We have the database of the salary and benefits paid to City employees since fiscal year 2013. Using this database, we are going to look at the total salary by job family groups, find most popular of them and visualize denisty of salaries for all of those groups. We'll find mean salary to understand general level of income.
  
Next, we are going to see health and dental benefits and find, which job families have those benefits above average.  
  
Then we are going to see the lowes paid jobs.

After this we'll move to organisations and discover, which organization groups give most benefits to their workers.
  
We'll find biggest overtime values to see how much emploees overwork. We'll also discover how big retirements contributions are.  

### Retail_Data_Analytics

Let's investigate dataset of sales to get understanding of factors that can predict sales of shops. We'll try to answer questions like if temperature alone can predict sale, check same for fuel price and some other variables. For this we'll build several simple linear regression models and try to predict one row from the dataset, which we would not include in the training dataset. Before doing this we'll investigate data to have initial understanding of what we shoul include in a model.  
  
Next, we'll try to build multiple regression model and figure out, whether some of the variables together can predict sales better.   
  
After doing this we'll check assumptions (which should be done before modeling, but since we have a goal of doing research about linear regression, we can do this after). Those assumptions will give us understanding of whether this data is a good fit for linear regression.

### Sport_Data_Analysis


We have a historical dataset with data about Olympic games and participants. Based on this dataset we should provide recommendations for best sport and sportsmen. We'll do some general investigations, such as percentage of participants, who got medals, their age and body metrics density, total quantity of medals.  
   
For sportsman we'll firstly investigate data, firstly checking for dependencies between males and females success. We'll be looking for dependencies between age and sport success (medals), and between body metrics, such as height and weight (converted into body mass index to be more representative). We'll get such values, as max and min, and also mean for body metrics to understand usual body constitution of male and female participants. Next, we'll assign some points (weights) to each type of medal (Gold, Silver, Bronze) and evaluate general score for each sportsmen. Based on this score we'll find the most succesfull sportsman (or sportsmen) and check his body metrics and age, whether they are in a statistically good intervals. Also we'll compare this sportsman to other participant and visualize this comparison.
   
For sports we'll check for all types of sport that took place at least once in our dataset, then for each of them we'll evaluate popularity, based on how much times this type of sport was hold during all years, how much teams participated in it during this time and how popular this sport was in last century (from 2000). Then we'll select top 10 by each popularity metric and print them to compare. Based on this comparison we'll recommend  the most popular sport to Kellogg.
