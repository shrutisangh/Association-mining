Association Rule Mining using Apriori Algorithm

This project demonstrates Association Rule Mining using the Apriori Algorithm in Python to identify frequent itemsets and discover relationships between products in transactional data.

Objective

The main objective of this project is to analyze customer purchase patterns using market basket analysis and generate association rules between items such as milk, bread, butter, and jam.

Technologies Used
Python
Pandas
mlxtend
TransactionEncoder
Apriori Algorithm
Association Rules
Dataset

A sample transactional dataset containing grocery items:

Milk
Bread
Butter
Jam

Each transaction represents items purchased together by a customer.

Steps Performed
Imported required libraries
Created sample transaction dataset
Applied TransactionEncoder for preprocessing
Converted transactions into a DataFrame
Used Apriori algorithm to find frequent itemsets
Generated association rules using confidence threshold
Displayed support, confidence, lift, and other metrics
Output

The project identifies:

Frequent itemsets like Bread + Butter
Strong association rules such as:
Bread → Butter
Jam → Butter

These insights help businesses improve product recommendations and shelf placement strategies.

Conclusion

Association Rule Mining is useful in discovering hidden patterns in customer purchases. This project provides a simple and practical implementation of Apriori Algorithm for understanding market basket analysis.
