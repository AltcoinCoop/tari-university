# Modeling 

- [Abstract](#abstract)

- [Question](#question)


## Abstract 

This paper sees the introduction of tools to model and describe the network attacks, allowing for the visualization and quantification of the threat on the blockchain. The model is used to describe the attacks. In this report we describe ways of using the model introduced and to quantify the risks of an attach by means of economic analysis. 

#### Question 

What is the probability that a malicious actor can control a majority of nodes in a randomly selected committee?



Variables 

- N= total available nodes 
- m= malicious nodes 
- n= committee size
- qp= minimum quorum percentage (50.1% and 66.7%)

#### Answer 

- N=100
- m= 10 (10% of the total available nodes are malicious)
- Randomly selected committee size =10 nodes 
- qp= 50.1% ($ 10 x 0.501=5.01 $ ) should we be saying 51%?
- What is the probability that you get at least six malicious node in the randomly chosen committee (what is the probability that a malicious actor can control a majority of nodes in a randomly selected committee?) 

You can choose 6 malicious nodes in 10C6 ways 

You can choose 10 nodes from the total nodes in 100C10 ways 

Thus 
$$
\frac
{\begin{array}{c}
10\\6
\end{array}}
{\begin{array}{c}
100\\10
\end{array}}
$$
So the required probability is 

$ 1.21E-11$



