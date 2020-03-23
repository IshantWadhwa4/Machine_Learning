Kmean
It is an unsupervise learning algo for clustring the data into different different classes, depending on the K value.
Imp. for this algo to run we need all numeric data, if we have non-odinal classes we use one hot encoding.

Steps for this algo:
   1. Select the value of K (This is what you have to decide)
   
   2. Randomly select K points and call them centroid
   
   3. Calculate distance b/w points and centroid. 
   
   4. min distance belong to that centroid.
   
   5. Repete the steps until you get the best results
   
   Elbow curve :
                Find the optimal value of K we use this curve.
                x = Kvalue
                y = SSD(Sum squred distance) (Euclidean distance)
