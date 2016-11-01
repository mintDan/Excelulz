# Path of mass through Action
The Excel sheet calculates the path of a thrown mass, in the single vertical dimension. Pressing "Vary Height" will change the object height, and calculate the action S. The true path of an object minimizes the Action integral S.

![Sint.png](https://github.com/mintDan/ExcelFun/tree/master/figs/Sint.png)

The Lagrangian L is given by L=T-V. Discretization of the Lagrangian gives

![Lapprox.png](https://github.com/mintDan/ExcelFun/tree/master/figs/Lapprox.png)

Which gives the discrete Action

![Sapprox.png](https://github.com/mintDan/ExcelFun/tree/master/figs/Sapprox.png)

Varying the path leads to different Actions, and varying w.r.t each node on the grid, gives an explicit linear system of equations.

![Svary.png](https://github.com/mintDan/ExcelFun/tree/master/figs/Svary.png)