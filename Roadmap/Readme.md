# Roadmap
Goal: To create a sophisticated SOM package. 
The main methods would be simulation, training, saving and loading a model, calculating distances, and creating plots. 
Regarding the plot methods, we need the functionality for displaying trained SOM information and for post-training analysis of other trained models.

## Time Schedule
- week 1: Topic Proposal
- week 2: 
- week 3:
- week 4:
- week 5:
- week 6 (~ Mar 12): Implementing Plot Functions in SOM class and  testing with Iris data
- week 7 (~ Mar 19): Implementing Plot Functions in SOM class and testing with Iris data by March 24 on Sunday
- week 8 (~ Mar 26):
- week 9 (~ Apr 2): 
- week 10 (~ Apr 9): 
- week 11 (~ Apr 16): 
- week 12 (~ Apr 23): Final Presentation, Final Journal Submission

## 1. SOM Packages Functionality

### 1.1 Plot functions
- [X] A. For cases in which there is one additional continuous variable associated with each item: (Lakshmi by March 24)
    - [X] A.1 Shade the hexagon with a greyscale or colorcode using the average of the variable accross the items iin each cluster or with the standard deviation of the variable across the items in the cluster.
    - [X] A.2 Make a histogram of the variable in each cluster
    - [X] A.3 Make a boxplot of the variable in ach cluster
    - [X] A.4 Make a violin plot of the variable in each cluster.
          
- [X] B. For cases in which there are one additional discrete variable (finite number of types, e.g. label # ) assosciate with each item: (Lakshmim by March 19)
    - [X] B.1 Shade the hexagon with a greyscale or colorcode using the average of the variable accross the items iin each cluster or with the standard deviation of the variable across the items in the cluster.
    - [X] B.2 Make a stem plot of the numbers of each variable type in each cluster.
    - [X] B.3 Make a pie chart of the percentage of each varriable type in each cluster.

- [X] C. For cases in which there are two continuous variables associated with each item: (Ei by March 24)
    - [X] C.1 make a scatter plot of the two variables in each cluster.
    - [X] C.2 Perform a regression between the two variables and plot the regression line in each cluster.
          
- [X] D. Hit Histogram (the hit histogram clud bee made with the original training data, or with a new set of data.

- [X] E. Neighbor distance plot (U-matrix)

- [X] F. Weight planes (Lakshmi by March 24)

- [X] G. Weight positions (Lakshmi by March 24)

- [X] H. SOM Topology

- [X] I. Neighbor connections. (Ei by March 24)

- [X] J. Complex Hit histogram: For hit histogram can ake interior of hexagon color coded to some additional variable and edges of hecagons couded to some other variable. Witdth of items in the cluster.
      
- [X] K. For any of plots, could have the size of the plots related to the number of items in the clusters. (Sometimes make the radius of the pie plots proportioanl to the number of items in the cluster.)

- [X] L. Plot a grey scale or color code with the hexagon related to the radius of the cluster (e.g., maximum distance of an item from the cluster center) 

- [X] M. Things to do by right cliking on a cluster and selecting from a pop up menu. (Ei by March 24)
    - [X] O.1 Plot the 5 (or any number) closest items to the cluster center.
    - [ ] O.2 Compute a sub-SOM for the items in the selected cluster

### 1.2 Save and Load Functions (SOM / Input data)
- [X] Save the trained SOM as pickle
- [X] Load the trained SOM as pickle
- [X] Save the indices of the items in the cluster.
- [X] Load the indices of the items in the cluster.

### 1.3 CuPy (GPU usability)
- [ ] Implement CuPy for faster computation

### 1.4 Documentation
- [ ] Add documentation to the functions

## 2. SOM Packages Testing with example data sets

### 2.1 Test the SOM packages as clustering method with some example datasets (text, CV, tabular, etc)
- [ ] Test the SOM packages with some example datasets with labels
- [ ] Get the Plot with them.

### 2.2 Test the SOM as post training tools for a trained model
- [ ] Train a neural network model with some example datasets and make a prediction.
- [ ] Get the confusion matrix of the prediction for the rained model
- [ ] Plot them with SOM cluster and compare them to get insight
