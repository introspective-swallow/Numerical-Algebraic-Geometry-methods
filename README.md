# Numerical Algebraic Geometry methods
Implementation of various Numerical Algebraic Geometry methods.

## Monodromy strategies for parametrized sparse systems
Jupyter notebook implementing and visualizing monodromy method algorithms from [[1]](#1) using the HomotopyContinuation Julia package. In particular, a parametrized family of sparse polynomials can be chosen and the following strategies are implemented to solve a generic system in it:
- Naive strategy
- Static strategy
- Dynamic incremental strategy

These last two strategies can be visualized as a gif, which shows the step-by-step progression of the homotopy graphs. The visualization can only be done using the flower graph.


## References
<a id="1">[1]</a> 
Duff, T., Hill, C., Jensen, A., Lee, K., Leykin, A., Sommars, J., 2016. Solving polynomial systems via homotopy continuation and monodromy. https://doi.org/10.48550/ARXIV.1609.08722
