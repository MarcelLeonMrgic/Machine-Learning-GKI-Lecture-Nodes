The perceptron is the foundation of every neural network.
![[Screenshot 2025-12-22 at 23.26.20.png]]

x_i are the input values
w_i are the weights 

Sigma: adds up the product of the input which is multiplied by its weight. 

Activation Function: if the Sum is bigger than Theta it will forward 1 and if its smaller it will forward 0. ![[Screenshot 2025-12-23 at 20.09.29.png]]
Instead of using a threshold you can make it 0 and put -Theta as a weight to a new input that is 1.
![[Screenshot 2025-12-22 at 23.33.07.png]]

How does learning works
1. choosing the topology
2. random init of weights
3. now the important part:
	1. implementing of a training vector