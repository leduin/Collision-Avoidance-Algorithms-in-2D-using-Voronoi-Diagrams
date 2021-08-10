<img
  src="https://www.yachaytech.edu.ec/wp-content/themes/yachay/images/header/logo-yachaytech.png"
  alt="yt_logo"
  width="200"
  align="right"
/>

<br/>
<br/>

## Simulation of Collision Avoidance Algorithms in 2D using Voronoi Diagrams
### Leduin José Cuenca Macas

##### Abstract

_Collision Avoidance_ is a classical scientific problem that prevents two or more moving objects from occupying the same place in space at a given time. Thus, this problem requests to minimize or eliminate the adverse alteration of the physical nature of moving objects. Furthermore, computer science has sought to solve this problem according to the increasing demands of technology. In this way, Collision Avoidance has a multidisciplinary character, appearing in mechanics, robotics, simulation, image processing, and even in the video game industry. For this reason, the computational implementation of the Collision Avoidance algorithms depends on the approach. One of them is the centralized system for holonomic multiple agents in a two-dimensional space, which we will analyze in the present work.

In this way, we will analyze some characteristics of Collision Avoidance implementations such as the execution time, the number of steps to converge to the total solution of the system, and the calculation of optimal values. Furthermore, through a review of the literature, we know that current implementations have advantages and limitations. For this reason, the present work aims to design a simulation where Collision Avoidance algorithms can be implemented. These algorithms are based on Voronoi Diagrams and Receding Horizon Control based on Quadratic Programming. Furthermore, we will seek to represent improvements, alternatives, or suggestions to previously detected limitations. For this, the comparisons will be made with the Optimal Reciprocal Collision Avoidance algorithm, widely used today.

The design and experiments in this work are incremental in style. In this way, we started from a relatively simple complexity according to prior knowledge to a higher one while researching the theoretical framework and state of the art. Then, using the Python Programming Language and the Anaconda Development Environment, we first implement Voronoi Diagrams and Buffered Voronoi Diagrams for a set of simulated holonomic robots arranged in a two-dimensional environment without static obstacles or passages. From this, we propose a simple Analytical Geometric Algorithm, using the geometric implementations present up to that moment, with a centralized information processing system. Subsequently, we select the parameters and configurations of the robots with the best performance to define our final optimal proposal using concepts from the Control Theory and Optimization areas, such as the Receding Horizons Control based on Quadratic Programming. Thus, we compared this proposal with other known methods, such as the Optimal Reciprocal Collision Avoidance algorithm implemented on a Cython-based Reciprocal Velocity Obstacle library, which is currently widely used in multi-agent systems motion. Finally, we show some results in a basic graphical simulation using tools like the Python Matplotlib library.

The Analytical Geometric Algorithm has successfully addressed and solved the limitations of execution time and the number of steps until convergence in the solution. On the other hand, the algorithm that uses Reverse Horizons Control based on Quadratic Programming requires more time to execute. When working with heuristics, we did not always obtain optimal results, but we did obtain good enough feasible solutions that are close to the high performance of the Optimal Reciprocal Collision Avoidance algorithm. However, the algorithm produces promising results with an accuracy of around 95\%.

After finishing this work, we recommend considering the advantages and limitations of the selected programming language, such as the precision of the numerical data types. Another recommendation is defining a range of values to test the performance of algorithm parameters according to the available computational resources. It is not unnecessary to suggest applying good programming practices such as modularization and code documentation. Likewise, for future work, consider using high-performance computing for massive data sets. The nature of the agent system and the environment can be modified to analyze the behavior of the algorithms. In this way, concurrency could be applied to decentralize the system and expand the dimension of the environment. For a better appreciation of the behavior, the simulation display can be improved. Finally, other solvers can be used for the optimization problem.
