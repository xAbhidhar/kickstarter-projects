# Kickstarter Projects
The goal of the project is to predict the success of a given kickstarter project. Given the dataset predict whether a kickstarter project will be sucesfull or not.

# Problem Statement 
To detect whether a project will fail or not based on the features in the dataset.

## Dataset
The dataset contains the following features:
 - usd_pledged
 - usd pledge real
 - usd goal real
 - ID 
 - Name
 - Category
 - Currency
 - Deadline
 - Goal
 - Launched
 
## Data preprocesing
Loaded the data to pandas dataframe.
Dropped in Columns with unceseeary features.
Removed NaN

## Implementation
Implemented the following algorothms:
### Algorithms
Implemented various algorithms like:
- Decision Tree
- Random Forest
- AdaBoostClassifier
- Gradient Boosting Classifier

## Output

## Results

Achieved the best result with the following algorithms:

- LightGBM Classifier

Light GBM is a gradient boosting framework that uses tree based learning algorithm. Light GBM grows tree vertically while other algorithm grows trees horizontally meaning that Light GBM grows tree leaf-wise while other algorithm grows level-wise. It will choose the leaf with max delta loss to grow. When growing the same leaf, Leaf-wise algorithm can reduce more loss than a level-wise algorithm.
