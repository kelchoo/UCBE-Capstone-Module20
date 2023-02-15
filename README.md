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

#### Results

•Expected data source(s) : https://www.kaggle.com/datasets/usernam3/shopify-app-store?select=reviews.csv

apps.csv
apps_categories.csv
categories.csv
key_benefits.csv
pricing_plan_features.csv
reviews.csv





#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information
