# Reference-Solution-for-PDEs
The goal of this repository is to create a reference solution for a PDE of interest using Spectral Methods(and others) with custom resolution.

So far, 1-dimensional Burgers' Equation, KdV Equation, and Allen Cahn Equation are implemented.(Time-dependent 1 dimensional PDEs)

The PDE solution can be obtained in the form of a matrix. in ".mat" file. 

The codes deal with 2-dim(spatial and temporal axes) solutions.

I used the same methodology that was employed in https://nbviewer.org/url/ignite.byu.edu/che541/lectures/spectral_.ipynb .

If you use my code to obtain your PDE solution, you can assume the solution is of form <img src="https://render.githubusercontent.com/render/math?math=u(x,t)=\sum_{n=-\frac{N}{2}+ 1}^{\frac{N}{2}}\hat{u}_n(t)e^{\frac{2\pi i n x}{L}}"> where <img src="https://render.githubusercontent.com/render/math?math=L =">the length of <img src="https://render.githubusercontent.com/render/math?math=x"> range, e.g., if <img src="https://render.githubusercontent.com/render/math?math=x\in[-1,1]">, <img src="https://render.githubusercontent.com/render/math?math=L = 1-(-1)=2">. Then, you can differentiate it w.r.t <img src="https://render.githubusercontent.com/render/math?math=x"> and plug into the PDE. All of the other processes can be carried out in a similar manner to these three equations.

Thanks!

Eunsuh, Kim, 2022-04-12, Pohang, Korea.

KdV Equation solver does not work properly:( I will fix it.
Eunsuh, Kim, 2022-05-20, Pohang, Korea.
