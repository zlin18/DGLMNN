# DGLMNN (Dynamic DGLM Neural Net)

![alt text](https://github.com/zlin18/DGLMNN/blob/main/Screen%20Shot%202021-03-04%20at%205.15.05%20PM.png)

The algorithm Nguelifack and Kemajou-Brown described uses a DGLM to update the mean and the variance of an estimation iteratively with the majorize-minorize algorithm. 

Here we take this algorithm and use it as a network optimizer. 

Objective function:
![alt text](https://github.com/zlin18/DGLMNN/blob/main/Screen%20Shot%202021-03-04%20at%205.29.26%20PM.png)

Rank based Wilcoxon dispersion function:
![alt text](https://github.com/zlin18/DGLMNN/blob/main/Screen%20Shot%202021-03-04%20at%205.29.33%20PM.png)

Residual:
![alt text](https://github.com/zlin18/DGLMNN/blob/main/Screen%20Shot%202021-03-04%20at%205.29.38%20PM.png)

Rank pseudo-norm (good with high leverage points):
![alt text](https://github.com/zlin18/DGLMNN/blob/main/Screen%20Shot%202021-03-04%20at%205.29.42%20PM.png)

# Files
This notebook takes 8 types of cryptocurrencies and applies a CNN & an RNN to predict gold price. 
It also tries to implement a custom DGLM optimizer
