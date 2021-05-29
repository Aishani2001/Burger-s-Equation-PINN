# Burger's Equation PINN
<br>
<br>
In this repository, I have used Physics Informed Neural Networks to solve the Burger's Equation. The Burger's Equation is a simplified version of the Navier Stokes Equation. Here, the velocity is in one spatial dimension and the external force is neglected and without any pressure gradient. We give the initial condition u(t=0,x)=-sin(x) and the boundary condition u(t, x=-1,+1)=0. The model predicts the value of u(t,x) for the input (t,x).
 <br><br>
 
 # About PINN <br>
 The PINN is a deep learning approach to solve partial differential equations. Well-known finite difference, volume and element methods are formulated on discrete meshes to approximate derivatives. Meanwhile, the automatic differentiation using neural networks provides differential operations directly. The PINN is the automatic differentiation based solver and has an advantage of being meshless.
 <br>
 
 # Reference<br>
 A detailed account of PINN is given in the following works : <br>
 - [https://arxiv.org/abs/1711.10561](https://arxiv.org/abs/1711.10561)<br>
 - [https://arxiv.org/abs/1711.10566](https://arxiv.org/abs/1711.10566)
 
 <br><br>
 In this notebook, I have implemented the PINN model with the L-BFGS-B optimization algorithm.<br>
 
 # Requirements: <br>
 - matplotlib <br>
 - scipy<br>
 - tensorflow<br>
 - numpy <br>

# Results<br>
Results can be viewed in 'output.png' file.
