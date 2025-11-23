# Telecom-Churn-Data-Mining-CaseStudy

**Goal:** Identify at-risk telecom business customers and recommend strategies to reduce churn.

**Project Summary:** 
This project applies data mining and customer segmentation techniques to reduce churn in the telecommunications industry. Using 8,454 business customer records, we cleaned and explored the data, segmented distinct business customer groups, and built predictive models to identify which accounts are most likely to leave.

I acted as both an analyst and coordinator, contributing to the core technical work (data prep, modeling, segmentation, visualizations) while synthesizing teammate work into a unified business solution that directly informs retention strategy.

**This project includes:**
- Data cleaning and removal of non-predictive identifiers to improve generalization
- Customer segmentation using clustering (Ward, K-Means, Average Linkage)
- Predictive modeling using decision trees, logistic regression, and neural networks
- Business-focused Tableau dashboards showing churn risk and customer behavior
- Strategic recommendations for loyalty programs and retention action

**Tech Stack:**
- SAS: Data preparation, clustering, decision tree, logistic regression, neural networks
- Tableau: Customer segmentation dashboards, churn risk visualization, business strategy summaries
  
*Links to Tableau visualizations and SAS results appear in the full paper*
  
**Key Results:**
A decision tree model emerged as the most effective tool for churn prediction, reducing the misclassification rate to 6.65% from an 11.76% baseline. The model identified clear churn indicators :

- Low active subscriber count
- Suspended accounts
- Assignment to non-GOLD CRM value segments


These findings translate into actionable next steps:
- Early outreach to low-engagement accounts
- Immediate support and intervention for suspended-line customers
- Tier-based loyalty offerings that target non-GOLD customer groups
- Value-aligned bundling and scalable plans for SOHO, SME, and enterprise clusters
  
Together, the model and segmentation approach enable telecom providers to proactively retain high-value customers, strengthen loyalty across value tiers, and surface overlooked accounts that are at risk of churn.

**Future Improvement Opportunity:** Improve churn prediction by addressing class imbalance and applying churn-focused modeling techniques (e.g., oversampling, cost-sensitive learning).
