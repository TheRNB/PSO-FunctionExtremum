# PSO-FunctionExtremum
An implementation of finding function exremum problem using Particle Swarm Optimization **from scratch**.

### FUNCTION DEFINITION
First we should define our function as defined in the notebook.

### HELPER FUNCTIONS
Since we are going to do vector multiplication and vector addition, we define the functions. (We could also utiliza the numPy library and include this function pre-written). We also need to Find the maximum value amongst our particles to check with our global maximum, so we define the function accordignly as well.

### INITIALIZATION
We now should initialize our starting variables:

n_particles: The number of particles in the swarm

IntertiaWeight: contains the intertia weight (w) of algorithm formula

cognitiveCoefficient = contains the cognitive coefficient (c1) of algorithm formula

socialCoefficient = contains the social coefficient (c2) of algorithm formula

max_iteration: max iterations of the algorithm

X: An array that stores the positions of the particles

V: An array that stores the velocities of the particles

F: An array that stores the values of the objective function for each particle

P: An array that stores the personal best positions of the particles

G: An array that stores the global best position of the swarm

best_cost: The best value of the objective function found so far

best_pos: Positions of the said values

## INFERENCE:
We should now run the algorithm to find the maximum value of the function.
