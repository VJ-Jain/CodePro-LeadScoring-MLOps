# CodePro LeadScoring MLOps Assignment
Build MLOps Pipelines to Preprocess data, Train & Infer using Pycaret, MLFlow, Airflow.

## Problem Statement
CodePro is an EdTech startup that had a phenomenal seed A funding round. 
It used the money to increase its brand awareness. As the marketing spend increased, it got several leads from different sources. Although it had spent significant money on acquiring customers, it had to be profitable in the long run to sustain the business. 
The major cost that the company is incurring is the customer acquisition cost (CAC).

At the initial stage, customer acquisition cost is required to be high in companies. But as their businesses grow, these companies start focussing on profitability. Many companies first offer their services for free or provide offers at the initial stages but later start charging customers for these services. For example, Google Pay used to provide many offers, and Reliance Jio in India offered free mobile data services for over a year. Once these brands were established and brand awareness was generated, these businesses started growing organically. At this point, they began charging customers.

Businesses want to reduce their customer acquisition costs in the long run. There are many ways to do that. You will learn about these methods in the next segment.

## Business goal
1. Improper targeting can be resolved by the marketing team. They can do so using better targeting strategies and using ad recommendations.
2. To resolve the issue of high competition, brand differentiation is required, which can be taken up by the product team.
3. To address inefficient conversion, the sales team must undergo upskilling and prioritise the leads generated.
4. The sales team must work with the data science team to figure out how to prioritise leads. The data science team must come up with lead scoring for all the leads generated.

The main objectives of lead scoring are as follows:

- Remove Junk by categorising leads on the basis of propensity to purchase
- Gain insights to streamline lead conversion and address improper targeting

creating three different pipelines for our use case.

1. Data Pipeline
2. Training Pipeline
3. Inference Pipeline

Since this is the first iteration of the model we are not aiming for high performance from the model but we are aiming to get value from the model as soon as possible by deploying the model into production, and then continuously improving our model once our baseline is deployed. Thus we will not focus much on developing the best possible model but we will make do with a simple model and focus more on deploying it into production.


