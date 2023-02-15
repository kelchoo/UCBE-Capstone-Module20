# UCBE-Capstone-Module20
Capstone Project MOdule 20
### Capstone Project 20.1: Initial Report and Exploratory Data Analysis (EDA)

Project Title: Building an App Store Intelligence Through Machine Learning for maximizing revenue, lower cost and reduce customer churn (Shopify Business Model)

Overview: In this module, I perfrom the actual ‘number crunching’ for your capstone project. I spent the time in creating and training models, as well as creating visualizations to make sense of your findings.

- Program learning outcomes addressed this module:

- Apply real-world tools to model and analyze real-world data

- Communicate foundational concepts about AI/ML

- Draw useful conclusions from real-world data

- Identify the best ML model to solve a problem

- Implement the ML/Data Science Life Cycle

I will show how I explore my data sources, test a few of the techniques, and come up with a solution or answer to your research question.

**Author: Kelvin Choo**

## Executive summary

• The research question you intend to answer (one sentence, if possible):

• As a Shopify Marketing Corporate Executive: how do I get a recommendation of the top apps which I should focus my marketing expenses when using the monthly reports provided (as shown in the data source as extracted from Shopify’s website in the link provided below) based on the various features and attributes of each app currently available on my store at the start of a given month (assuming the files have been provided in the point below from Shopify’s internal database to the marketing team) so I can maximize revenues for each month ? 


The above data sources contains the following key attributes about the apps currently offered on Shopify website for its merchants to download, purchase and use for various purposes that include increasing sales, simplify processes for completing the sales and invoicing processes or even promoting its website and measure revenue and forecasts inventory and sales growth.

Data includes:  App Counts, App Store review, pricing hints, descriptions, review counts, ratings, the various pricing plans offered for app developers

## Rationale
Why should anyone care about this question?


## Research Question
how do I get a recommendation of the top apps which I should focus my marketing expenses when using the monthly reports provided (as shown in the data source as extracted from Shopify’s website in the link provided below) based on the various features and attributes of each app currently available on my store at the start of a given month (assuming the files have been provided in the point below from Shopify’s internal database to the marketing team) so I can maximize revenues for each month ? 

## Data Sources
What data will you use to answer you question?




## Methodology
What methods are you using to answer the question?

### Step 1: Understanding the Data

To gain a better understanding of the data:
· Libraries are imported and aliased correctly
· Appropriate plots for categorical and continuous variables are utilized
· Demonstrates competency with pandas
· Demonstrates competency with seaborn
· Variables are sensible
<img width="349" alt="image" src="https://user-images.githubusercontent.com/115063137/218887704-144c1a55-3abd-45d6-9470-d1eeffa1cfca.png">

### Step 2: Read in the Data

Use pandas to read in the datasets` and assign to a meaningful variable name.

<img width="2076" alt="image" src="https://user-images.githubusercontent.com/115063137/218887834-f538d032-48d0-4e50-9751-a602a8219bcb.png">
Creating joins and merge data to create meaningful linkage between apps, reviews and categories 
<img width="1349" alt="image" src="https://user-images.githubusercontent.com/115063137/218887882-3eca82e7-2aca-400a-9b05-9881c2788583.png">

### Step 2.1 creating joins with pricing and categories and factorize the data for easy identification and joining the data.
<img width="986" alt="image" src="https://user-images.githubusercontent.com/115063137/218888259-1b43ba2c-f247-4788-b1a0-f5931f8c313a.png">


### Step 2.2 Creating dataframes with joined data

<img width="1374" alt="image" src="https://user-images.githubusercontent.com/115063137/218888481-4220c4d1-d1a1-480f-9d87-e47167495c8e.png">

### Step 3 Build Visuallizations to answer the following questions: 
- how do I identify as an executive managing an app store, what are my top performing categories of apps in terms of reviews (total), positive ratings, create a summary scoring system to identify my top category of apps.
- identify possible revenue potential from these top reviews/purchases 
- recognize and point out clear risks to revenue

<img width="2075" alt="image" src="https://user-images.githubusercontent.com/115063137/218888614-bac8886c-c038-40cd-8b2a-8729b54619a3.png">

<img width="2080" alt="image" src="https://user-images.githubusercontent.com/115063137/218889069-447156e7-7fec-411c-8d73-4350d99469a8.png">

<img width="2087" alt="image" src="https://user-images.githubusercontent.com/115063137/218889125-95924139-ea0e-4b89-aef6-117a06acd54e.png">
As observed that the top categories are Store Design, Conversion, Marketing for which reviews are driving the response on merchants using Shopify apps to generate sales to their websites and storefront.
Here the top app reviews give us a preview of the potential apps that we need to confirm that the reviews are key to ensuring their sustainability.

<img width="2037" alt="image" src="https://user-images.githubusercontent.com/115063137/218889795-6f2ca81e-cd40-4e94-b223-2823c4457a3c.png">
The top categories as shown here above confirm the pricing structure that works best for app.

### Step 4 Understanding the Features

<img width="1584" alt="image" src="https://user-images.githubusercontent.com/115063137/218898115-b1592de7-cc51-44a8-9047-9569093c2372.png">

<img width="1559" alt="image" src="https://user-images.githubusercontent.com/115063137/218898183-0d4e5a8e-4cf4-49ea-a58f-f86625786c39.png">
<img width="1332" alt="image" src="https://user-images.githubusercontent.com/115063137/218898221-3d30817d-a7e6-4e68-9937-80577f050b1e.png">
<img width="1560" alt="image" src="https://user-images.githubusercontent.com/115063137/218898301-04d2c9b9-af8d-4415-83ad-b27989e175ec.png">

<img width="1351" alt="image" src="https://user-images.githubusercontent.com/115063137/218898396-d4a0c0f3-1f65-43a5-bea5-86f9ebd83675.png">
Correlation helps build the confidence and understanding that the user rating for using the app is a great feedback loop for the developer and for Spotify to feel te pulse of the merchant using its app and provides good understanding through the words used in the review which we will cover next in our models and clustering techniques used.

### Step 5: Understand the task and modeling
Business Objective of the task:

- find a model that can explain success of the product/app.

Such model can increase campaign efficiency by :

-- identifying the main characteristics that affect success,

-- helping in a better management of the available resources

-- and selection of a high quality

-- and affordable set of potential buying customers.

we use a combination of KMeans clustering and PCA as well as TSNE to breakdown the relationshp further between what the developer sees as features driving the ratings and reviews of the app developed for Shopify's merchants.

Continuing to clean the data and scrub for redundant columns after merging continues to be important as we drive towards the solution
<img width="1578" alt="image" src="https://user-images.githubusercontent.com/115063137/218898914-799e3c70-cdb0-4fa5-9281-f4d3154253fb.png">

Using NLP techniques, Shopify executives can really understand how the words used in reviews can be "nuggets" for building customer loyalty and branding knowledge for the apps that are popular and the ones that are not can really get the feedback needed to understand what is causing poor take rate and downloads by merchants:

<img width="1577" alt="image" src="https://user-images.githubusercontent.com/115063137/218899162-479f1a0b-7e14-44f4-a357-efc79fb27148.png">


#### Results

•Expected data source(s) : https://www.kaggle.com/datasets/usernam3/shopify-app-store?select=reviews.csv

apps.csv
apps_categories.csv
categories.csv
key_benefits.csv
pricing_plan_features.csv
reviews.csv

With Vectorization, chi square and SentimentAnalyzer text search tools we can truly magnify the category of apps and the respective grouping of words that point out the risks to growth of the app store.
<img width="1462" alt="image" src="https://user-images.githubusercontent.com/115063137/218899617-ed57d52e-1754-49b3-b8be-6507eb154d4b.png">

<img width="503" alt="image" src="https://user-images.githubusercontent.com/115063137/218899646-0a01900e-be7f-4f5e-b6dd-56f4189778da.png">


<img width="1788" alt="image" src="https://user-images.githubusercontent.com/115063137/218899684-e49aac76-0b47-46af-8721-73ca59ac5358.png">

<img width="1747" alt="image" src="https://user-images.githubusercontent.com/115063137/218899761-51f6954c-ec6b-4f5a-9b5a-8bc21c51281f.png">

## Conclusion
With the top apps and developers identified to drive the potential revenues and stickiness of the ego systems of apps, the company can now repeat this process at the end of each month to do the following:
1. maxmize the revenue of looking at promoting the app on the above list more during the month ahead
2. focus more on the risk area in terms of investing on reducing fraud
3. improving Shopify's own apps based on the ratings and feedback provided through the repeated process above.


#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information
