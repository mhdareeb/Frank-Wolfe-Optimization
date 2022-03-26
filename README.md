# Frank-Wolfe-Optimization
This paper presents a stochastic descent algorithm that applies to constrained optimization and is particularly efficient when the objective function is slow to evaluate and gradients are not easily obtained, as in some PDE-constrained optimization and machine learning problems.

The basic algorithm projects the gradient onto a random subspace at each iteration, similar to coordinate descent but without restricting directional derivatives to be along the axes and applies Frank-Wolfe using that gradient direction.

The paper provides proofs of convergence under convexity assumption and presents favorable results when compared to subspace gradient descent on different constraints.
