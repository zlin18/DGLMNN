# DGLMNN (Dynamic DGLM Neural Net)

#![alt text](http://url/to/img.png)

The algorithm Nguelifack and Kemajou-Brown described uses a DGLM to update the mean and the variance of an estimation iteratively with the majorize-minorize algorithm. 

Here we take this algorithm and use it as a network optimizer. 

Objective function:
# ![alt text](http://url/to/img.png)

Rank based Wilcoxon dispersion function:
# ![alt text](http://url/to/img.png)

Residual:
# ![alt text](http://url/to/img.png)

Rank pseudo-norm (good with high leverage points):
# ![alt text](http://url/to/img.png)

# Files
This notebook takes 8 types of cryptocurrencies and applies a CNN & an RNN to predict gold price. 
It also tries to implement a custom DGLM optimizer
