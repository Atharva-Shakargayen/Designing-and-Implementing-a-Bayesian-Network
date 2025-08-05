# Designing-and-Implementing-a-Bayseain
Meera is an online portal for Gems and Jewellery. They have launched a Diwali marketing
campaign aimed at increasing customer purchases. The management wants to analyze the
success of this campaign based on various customer attributes using a Bayesian Network.
Dataset Description (100 Records Provided)
Each row in the dataset represents a customer with the following attributes:
 Age Group – Categorized as:
o Age &gt; 35
o Age ≤ 35
 Gender – Male / Female
 Business – Whether the customer has a business (Yes/No)
 Employed – Employment status (Yes/No), influenced by Business
 Marital Status – Married / Single, influenced by Age Group
 Success – Whether the customer responded positively to the marketing campaign
(Yes/No)
Bayesian Network Structure
Dependency Relationships:
 Age Group → Marital Status
 Age Group → Success
 Gender → Success
 Business → Employed
 Employed → Success
 Marital Status → Success

Implement a Bayesian Network model:
 Define the structure based on the attributes and their dependencies.
 Add Conditional Probability Distributions (CPDs) with hypothetical probabilities (or
from dataset analysis).
 Validate your Bayesian Network using .check_model().
 Query the network for P(Success | Gender, Age Group).
