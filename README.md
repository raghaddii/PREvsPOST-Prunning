# PREvsPOST-Prunning
Apply pre and post pruning for DT and compare results with reasons.

# Result
As a result Post-pruning is more efficient than pre-pruning in our data, depend on some cretiria :

- Depth: The results were different every run, so we applied the average for 10th times  
  
Depth before pre-pruning :10.7 
Depth after pre-pruning :4 
  
Depth before post-pruning: 10.2 
Depth after post-pruning: 2.9 

By observing the average depth, we can see that the post pruning prune levels more than pre pruning. 

- Accuracy : the train and test score of the pre and post pruning by taking the average for 10th times 
  
Train = 0.865 for pre 
Test = 0.764 for pre 
  
Train = 0.819 for post 
Test = 0.796 for post 
  
We can clearly see that the train and test score in both pre-pruning and post-pruning are kind of close to each other, and that means the overfitting is solved. 
 
Therefore, in post-pruning the score i so close compared to the score in pre-pruning, that is a good credit for post-pruning since the test data is small compared to the train data but we can see that the accuracy in test is so close to the train. 
As a result of the evaluation, we can say that the post-pruning outperforms the pre-pruning considering the computation we did. 
