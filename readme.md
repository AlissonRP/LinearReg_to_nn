## Linear Regression from scratch

Linear Regression is one of if not the best known statistical model, the classic approach is to estimate the parameters by least squares, but here we are going to use gradient descent and show that linear regression is just a particular case of a neural network. 

<p align="center"><img align="center" src="https://www.aquila-consortium.org/assets/posts/nn/w_init.gif" height="310px" width="690"/></p>

To know if the estimation is correct, we will simulate data with NumPy, the optimization will be made using PyTorch
