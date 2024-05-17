# Final-Project-Statistical-Modelling-with-Python

This project aims to explore and utilize statistical modeling techniques using Python for comprehensive data analysis. Leveraging the power of Python's
rich ecosystem of libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Sciki-learn, the project seeks to delve into various statistical concepts
and methodoligies to derive actionable insights from data.

## Project/Goals

1. Mastery of Python Fundamentals:
  
  
   Begin by solidifying proficiency in Python programming, encompassing core concepts like variables, loops, conditionals,
   functions, and data structures. This foundational knowledge will serve as a springboard for the subsequent statistical modeling tasks.

2. Understanding Statistical Concepts:
  
   Gain a deep understanding of fundamental statistical principles, including probability distributions, hypothesis testing,
   regression analysis, and statistical inference. This comprehension lays the groundwork for effective application of statistical modeling    
   techniques.

3. Exploratory Data Analysis(EDA):

   Practice conducting EDA on diverse datasets to uncover patterns, trendsm and anomalies. Utilize visualization libraries
   like Matplotlib and Seaborn to create insightful plots and graphs that facilitate data exploration and interpretation.

4. Linear Regression:

   Master the implementation of linear regression models for modeling relationships between variables. Learn to assess model assumptions,
   perform diagnostics, and interpret regression coefficients to extract meaningful insights from data.

5. Logistic Regression:

   Extend modeling capabilities to classification problems through logistic regression. Develop proficiency in building binary and
   multinomial logistic regression models, evaluating model performance, and interpreting coefficients to make informed decisions.

6. Real-world Applications:

   Apply acquired statistical modeling skills to real-world datasets and problems across diverse domains.
   Engage in hands-on projects to address practical challenges and derive actionable insights from data.
   
Conclusion:

Through systematic exploration and application of statistical modeling techniques with Python, this project aims to empower one with the knowledge and 
skills to extract valuable insights from data, make data-driven decisions, and drive positive outcomes across various domains.
By achieving the outlined goals, one will emerge proficient in statistical modeling with Python, equipped to tackle complex data analysis challenges with confidence and efficacy.

## Process

The process involved in this project involved several steps.

1. Define the problem and objectives

   Explore the data retrieved from the city bikes, yelp and foursquare API, join this data using python with focus 
   on the city of London, Uk.

2. Filter this data and analyze this data.
   
   This process allows for first filtering the data to find out the information necessary/relevant, looking at 
   information valuable to be used to enable a business make important decisions, which can contribute to being 
   able to draw conclusions from the findings from of this data and its potential impact. Use Dataframe to filter 
   this data to make it more readable.
  
4. Document the results gotten from the retrieved data and process it by using visualization such as histogram etc 
   to present these findings to stakeholders as well as make recommendations or insights based on analysis 
   retrieved from this data.

5. In the process of data wrangling I worked with two data sources as earlier mentioned yelp and foursquare were 
   the data was pulled from. The data pulled was human readable after it was placed in Dataframe.

6. Data Preprocessing: This was needed, to process data by handling missing values, encoding categorical 
   variables, and scaling numerical features, it allows the Dataframe to process this data to make it more 
   readable.

7. In using regression, the algorithm showed how Mean Squared Error: 3.944304526105059e-31 and R-squared Score: 
   0.0 which showed that the data retrieved was good.


## Results




The results gotten from this data showed

1. City bikes API produced more details from queries generated than the other API used.
   ![image](https://github.com/Ayiwoma/Statistical-Modelling-Project/assets/141646278/7bc2d930-64ee-4cd3-a120-71c1af93b4c1)

2. City  API provided more details regarding points of interest, the data gotten was very relevant to the analysis used, 
   which made it easier to draw references from results gotten. Some of this were location, name of station, capacity,       restaurant name 
   and category.

   101, 'Aldwych Underground Station', 20, 'Dishoom', 'Indian', 4.5
   
   101, 'Aldwych Underground Station', 20, 'Barrafina', 'British, Steakhouses, Cocktail Bars', 4.4
   
   101, 'Aldwych Underground Station', 20, 'The Admiralty', 'Steakhouses, British', 3.8
                      
3. Foursquare API had some limitations although it did produce relevant results but it was not as detailed as using the 
   data gotten from yelp which was more detailed
![image](https://github.com/Ayiwoma/Statistical-Modelling-Project/assets/141646278/7fec7319-8298-43b9-8202-2641dcf54f57)


5. Merging this data, showed that yelp was able to provide more detailed results than foursquare.



![image](https://github.com/Ayiwoma/Statistical-Modelling-Project/assets/141646278/177ce7f6-9782-4be3-97b4-3cdee82be675)

6. Comparing top restaurants data gotten from yelp API and foursquare API
   In coverage yelp API showed from its data that it had more coverage than foursquare API
   In ratings yelp API gave more details in its results and a higher rating than the foursquare API
   Finally the yelp API showed more details in the address shown in its results from the data generated.

   Top 10 Restaurants from Yelp:

   African Volcano, Rating: 5.0
   
   Nepa Coffee & Food, Rating: 5.0
   
   Rainforest Creations, Rating: 5.0
   
   Skewers, Rating: 5.0
   
   Holloway Best Kebab, Rating: 5.0
   
   The Black Cab Coffee Co, Rating: 5.0
   
   Camberwell Arms, Rating: 5.0
   
   Blue Orchid Chinese Restaurant, Rating: 5.0
   
   Oi Vita Pizzeria, Rating: 5.0
   
   Chokhi Dhani, Rating: 5.0

## Challenges 



The challenges acquired in this project showed that some API produced more information than others, in using foursquare API data did not produce as much details as yelp and city bike, this limited comparison in areas like ratings as I was unable to compare the data from yelp and foursquare using the parameter of ratings because foursquare did not have ratings data availble.

## Future Goals



Explore another city to compare if foursquare API will provide more detailed data than collected, this is because the data retrieved compared to the other API had missing values for the city London UK which was used, it would have shown if the challenges achieved when trying to retrieve the data would not have happened if I had used another city.
