# Discovery-of-Frequent-Itemsets-and-Association-Rules
* Introduction
  * The problem of discovering association rules between itemsets in a sales transaction database (a set of baskets) includes the following two sub-problems [R. Agrawal and R. Srikant, VLDB '94 (Links to an external site.)]:
    * Finding frequent itemsets with support at least s;
    * Generating association rules with confidence at least c from the itemsets found in the first step.
Remind that an association rule is an implication X → Y, where X and Y are itemsets such that X∩Y=∅. Support of the rule X → Y is the number of transactions that contain X⋃Y. Confidence of the rule X → Y the fraction of transactions containing X⋃Y in all transactions that contain X.

* Task
  * You are to solve the first sub-problem: to implement the A-Priori algorithm for finding frequent itemsets with support at least s in a dataset of sales transactions. Remind that support of an itemset is the number of transactions containing the itemset. To test and evaluate your implementation, write a program that uses your A-Priori algorithm implementation to discover frequent itemsets with support at least s in a given dataset of sales transactions.
  * The implementation can be done using any big data processing framework, such as Apache Spark, Apache Flink, or no framework, e.g., in Java, Python, etc.  

* Optional task for extra bonus
  * Solve the second sub-problem, i.e., develop and implement an algorithm for generating association rules between frequent itemsets discovered by using the A-Priori algorithm in a dataset of sales transactions. The rules must have support at least s and confidence at least c, where s and c are given as input parameters.
