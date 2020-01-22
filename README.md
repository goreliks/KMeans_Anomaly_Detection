# KMeans_Anomaly_Detection
Anomaly Detection using KMeans

The wood pallet manufacturing plant produces desks in 5 different series. The CSV file named 'data' containing dimension (length and width) data of 10,000 plates from all 5 series:
1. 10X10 square desks 
2. 15X15 square desks
3. 30X30 square desks
4. 15X10 rectangular desks
5. 20X10 rectangular desks

We must classify each desk to the group to which it belongs using the k-means algorithm and to find all valid desks, desks shall be defined valid if they are at least 3 cm from the cluster center to which they are associated.

• A graph showing the desks of all dimensions, when each group is marked with a different color

• A graph showing the desks of all dimensions, when a normal plate is colored in blue and a plate is colored in red

In addition, we will do a sensitivity analysis where we show (on the graph) the percentage of defected desks that depend on the threshold by which we decide whether desk are valid or not.

Write to the csv file named 'anomaly detection' the results of clustering ( threshold 3 cm )
