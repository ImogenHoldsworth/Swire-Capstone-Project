# Swire Capstone: Customer Growth Modeling
This repo contains my personal work for the Swire Coca-Cola Capstone Project (Spring 2025, Group 2, University of Utah MSBA Program).

# Summary of Business Problem & Project Objective

Swire Coca-Cola serves a large number of customers, but some do not order enough volume  to make internal delivery (red truck) cost-effective. Currently, Swire doesn’t have a systematic method for identifying which low-volume customers are on a growth trajectory and should be retained on the red truck route.

The objective of this project was to use customer data to identify potential and emerging customers who are approaching key volume thresholds (e.g., 400 gallons/year). By identifying these accounts, Swire can avoid prematurely transitioning high-potential customers to white truck delivery and instead nurture their growth internally.

# Group Solution
We approached the problem through data segmentation and predictive modeling. 
Our steps included:
- Exploratory data analysis to understand customer behavior and traits
- Building logistic regression and multilevel models to predict which customers would surpass the 400-gallon threshold in 2024
- Creating customer segments based on order trends and growth patterns
- Proposing a framework to guide future delivery routing and retention strategy

# My Contribution to the Project
This repo contains my personal work, including:
- Exploratory data analysis to investigate customer distribution, location clusters, and key traits.
- Data cleaning and file joining.
- Developing and refining logistic and multilevel models to predict growth on Retailer customers. 
- Identifying challenges in modeling customer volume due to wide variance for Retailer customers. 
- Testing different segmentation approaches to improve model performance for Retailer customers.
- Develop visual presentation and narrative for business solution. 

# Business Value of the Solution
 This project provides Swire with a data-driven framework to:
- Protect future profitable customers by identifying them early
- Make more confident routing decisions based on predicted performance
- Improve operational efficiency by aligning delivery method with customer potential

# Difficulties Encountered
- Customer volume data was right highly skewed, making modeling and interpretation tricky
- Many traits (like delivery channel or partner status) were sparse or unevenly distributed, and mostly statistically insignficant
- It was difficult to isolate features that consistently drove high order volume
- Choosing the right balance between model complexity and interpretability was an ongoing challenge
- Limited historical order data made it difficult to build and test predictivite capability of the models.

# What I Learned
- How to use multilevel modeling to account for group-level effects (retailers and customer segments)
- The importance of thoughtful customer segmentation in model performance
- How to clean and analyze real-world, messy data
- How to translate predictive model output into actionable business insights
- How to present findings to real stake holders
- How to work alongside others to ensure goals are met

# Author
Imogen Holdsworth University of Utah, MSBA – Spring 2025
