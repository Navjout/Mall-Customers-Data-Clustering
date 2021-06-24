# Mall-Customers-Data-Clustering
Malls or shopping complexes are often indulged in the race to increase their customers and hence making huge profits. To achieve this task machine learning is being applied by many stores already. It is amazing to realize the fact that how machine learning can aid in such ambitions. The shopping complexes make use of their customers’ data and develop ML models to target the right ones. This not only increases sales but also makes the complexes efficient.

### Task 1 : Importing libraries and data
We imported the librabies that are used: pandas, numpy, seaborn, matplotlib

- Here we have the following features for 200 customers:

CustomerID: It is the unique ID given to a customer

Gender: Gender of the customer

Age: The age of the customer

Annual Income(k$): It is the annual income of the customer

Spending Score: It is the score(out of 100) given to a customer by the mall authorities, based on the money spent and the behavior of the customer.

### Task 2 : Data Cleaning 
Dropping the duplicate values

Checking missing values

### Task 3 : Plotting the graph
Here we will plot the graph and see the data of the customer according to their age, annual income and spending score.

According to gender we plotted graph, female customers are more

### Task 4 : Data Clustering using KMeans
Here using KMeans we plotted a graph to see the customers spending score according to their income.

# Conclusion:
Analyzing the Results We can see that the mall customers can be broadly grouped into 5 groups based on their purchases made in the mall. In cluster 4(yellow colored) we can see people have low annual income and low spending scores, this is quite reasonable as people having low salaries prefer to buy less, in fact, these are the wise people who know how to spend and save money. The shops/mall will be least interested in people belonging to this cluster. In cluster 2(blue colored) we can see that people have low income but higher spending scores, these are those people who for some reason love to buy products more often even though they have a low income. Maybe it’s because these people are more than satisfied with the mall services. The shops/malls might not target these people that effectively but still will not lose them. In cluster 5(pink colored) we see that people have average income and an average spending score, these people again will not be the prime targets of the shops or mall, but again they will be considered and other data analysis techniques may be used to increase their spending score. In cluster 1(red-colored) we see that people have high income and high spending scores, this is the ideal case for the mall or shops as these people are the prime sources of profit. These people might be the regular customers of the mall and are convinced by the mall’s facilities. In cluster 3(green colored) we see that people have high income but low spending scores, this is interesting. Maybe these are the people who are unsatisfied or unhappy by the mall’s services. These can be the prime targets of the mall, as they have the potential to spend money. So, the mall authorities will try to add new facilities so that they can attract these people and can meet their needs. Finally, based on our machine learning technique we may deduce that to increase the profits of the mall, the mall authorities should target people belonging to cluster 3 and cluster 5 and should also maintain its standards to keep the people belonging to cluster 1 and cluster 2 happy and satisfied.




