# Reference-Solution-for-PDEs
This repository aims at making a reference solution to PDE of interest using Spectral Methods(and others) with custom resolution.

So far, 1-dimensional Burgers' Equation, KdV Equation, and Allen Cahn Equation are implemented.(Time-dependent 1 dimensional PDEs)

One can get the PDE solution that looks like a matrix in ".mat" file. 

The codes are treating 2-dim(spatial and temporal axes) solutions.

I followed the methodology used by https://nbviewer.org/url/ignite.byu.edu/che541/lectures/spectral.ipynb .

If one wants to apply my code to get your PDE, you can assume the solution is of form <img src="https://render.githubusercontent.com/render/math?math=u(x,t)=\sum_{n=-\frac{N}{2}+ 1}^{\frac{N}{2}}\hat{u}_n(t)e^{\frac{2\pi i n x}{L}}"> where <img src="https://render.githubusercontent.com/render/math?math=L =">the length of <img src="https://render.githubusercontent.com/render/math?math=x"> range, e.g., if <img src="https://render.githubusercontent.com/render/math?math=x\in[-1,1]">, <img src="https://render.githubusercontent.com/render/math?math=L = 1-(-1)=2">. Then, you can differentiate it w.r.t <img src="https://render.githubusercontent.com/render/math?math=x"> and plug into the PDE. All the other process can be done with analogous way to Burgers', KdV, and Allen Cahn Equation.

Thanks!

Eunsuh, Kim, 2022-04-12, Pohang, Korea.
