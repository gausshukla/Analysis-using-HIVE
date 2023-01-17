# Analysis-using-HIVE

PROJECT DESCRIPTION
The project aims to display Beverages-to-Multiple Branches of one Coffee Shop (many-to-many relation) using Hive. In other words, each Beverage might be available on many Branches, and each Branch of the Coffee shop might distribute many Beverages.
Assuming each branch send their sales report as a csv file. The project aims to stage them to HDFS and further analysis to be performed using Hive for the given problem statement below.

The description of the data is as below

- Beverages Name does not have spaces.
- Coffee shop Branches have mentioned as Branch1, Branch2 and etc.
- Beverages can be ordered many times, with different counts
- A Beverage and Branch combination might appear multiple times
- Beverages could be available on multiple Branches
- The output should have no commas or punctuation, only 1 space between the Beverages and Count of Consumed people.



PROBLEM STATEMENT

- What is the total number of consumers for Branch1?
- What is the number of consumers for the Branch2?
- What is the most consumed beverage on Branch1?
- What are the beverages available on Branch10, Branch8, and Branch1?
