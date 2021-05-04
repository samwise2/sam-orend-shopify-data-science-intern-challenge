# Shopify Data Science Intern Challenge
Welcome to the repo for my Shopify Data Science Internship Challenge!

## Solutions

You can view my in-depth solutions to the challenge questions here: https://www.kaggle.com/samorend/sam-orend-shopify-data-science-intern-challenge

I have detailed answers for both Question 1 and 2 at that link. 

## Design Choices

- I chose to use Kaggle because it provides a web-based data science environment that would allow me to quickly analyze the provided dataset. Kaggle also made it very easy to publish my Jupiter Notebook online so that it can be easily shared in the link above!
- I used Python with Pandas to analyze the dataset for Question 1. 
  - Pandas allows me to easily create dataframes for varius input file types (ex: .csv)
  - Panadas also provides various high-level methods that I thought would be helpful in determining what might be going wrong with our naive AOV calculation. I.e. built in `sort_values`, `describe` etc. These methods allow us to quickly see statsitical summaries of the dataset, and also sort the data set by specific criterion. This mix of summary data, and filtered detailed data was very beneificial.
  - Alternatively `R` would have been a great choice for analyzing this data as it is a programming language catered to data analysis and may have been a better choice than Python in this case. But I did want to demonstrate my familiarity with Python instead since it has broader data science applicability including: machine learning and deployment/production use cases.
