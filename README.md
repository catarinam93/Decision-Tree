# Decision-Tree
Third assignment of the course Artificial Intelligence (2nd year, 2nd semester)

## A little context
### Overview
This project focuses on implementing an algorithm for the induction of decision trees similar to ID3, as described in Chapter 19 of the textbook "Artificial Intelligence: A Modern Approach" by Peter Norvig and Stuart Russell. The algorithm uses entropy as the node selection function and is capable of learning decision trees from a set of observations provided in CSV format.

### Functionality
The program takes a set of examples in CSV format as input, where each example contains several attributes (columns) and a class variable (last column) for classification. It constructs a decision tree model based on the provided examples using the ID3 algorithm with entropy-based attribute selection.

#### Input Format
The input CSV file should contain multiple attributes and a class variable, with each row representing an example. The class variable should have multiple distinct values corresponding to different classes.

#### Output Format
The output of the program is a decision tree represented in a specific format. Each node in the tree corresponds to an attribute, and each branch represents a possible value of that attribute. The class value assigned to each branch corresponds to a leaf node in the tree. The output also includes counters representing the frequency of examples corresponding to each branch.

## Example Datasets
Several example datasets are provided for testing purposes:

* restaurant.csv: Contains information about customers and restaurants, with the task of predicting whether a customer will wait to eat at a restaurant.
* weather.csv: Contains information about climate conditions for playing tennis, with the task of learning a decision tree to determine the best conditions for playing tennis.
* iris.csv: Contains numerical information about iris plants, with the task of classifying plants into different species based on their attributes.
