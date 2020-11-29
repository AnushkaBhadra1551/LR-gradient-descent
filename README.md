# LR-gradient-descent
Gradient descent from scratch.

Gradient Descent is a very generic optimization algorithm capable of finding optimal solutions to a wide range of problems. 
The general idea of Gradient Descent is to tweak parameters iteratively in order to minimize a cost function. An important 
parameter in Gradient Descent is the size of the steps, determined by the learning rate hyperparameter. If the learning rate
is too small, then the algorithm will have to go through many iterations to converge, which will take a long time. On the 
other hand, if the learning rate is too high, you might jump across the valley and end up on the other side, possibly even 
higher up than you were before. This might make the algorithm diverge, with larger and larger values, failing to find a good
solution.
