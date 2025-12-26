The perceptron is the foundation of every neural network.
![[Screenshot 2025-12-22 at 23.26.20.png]]

x_i are the input values
w_i are the weights 

Sigma: adds up the product of the input which is multiplied by its weight. 

Activation Function: if the Sum is bigger than Theta it will forward 1 and if its smaller it will forward 0. ![[Screenshot 2025-12-23 at 20.09.29.png]]
Instead of using a threshold you can make it 0 and put -Theta as a weight to a new input that is 1.
![[Screenshot 2025-12-22 at 23.33.07.png]]

How does learning with a perceptron works
1. choosing the topology
2. random init of weights
3. now the important part:
	1. implementing of a training vector $X_i, t_i$  with $X_i$ as the input Vector and $t_i$ as the expected result. for example $v_1 = ([1,1,0],1)$ 
	2. calculation of $o_i$ the real result :
	3. regulation of the weights if $o_i$ is not $t_i$ :
			![[Screenshot 2025-12-24 at 03.19.53.png]]
			$w_ij$ is the weight from neuron i to neuron j
			$\delta_t$ is the error calculated by the expected output minus the real output.
			$\alpha$ is the learning rate a number between 0 and 1 . if the learning rate is to low it wouldn't change much but a learning rate to high would change it to much
			x_i is the input of the weight.