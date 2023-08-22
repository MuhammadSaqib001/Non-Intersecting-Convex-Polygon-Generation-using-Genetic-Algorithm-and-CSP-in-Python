# Non-Intersecting Convex Polygon Generation using Genetic Algorithm and CSP

This project generates non-intersecting convex polygons in n dimensions using a combination of Genetic Algorithm and Constraint Satisfaction Problem (CSP) techniques. The goal is to evolve a population of polygons that adhere to geometric constraints, ensuring non-intersecting, convex shapes.

### List of Constraints for the polygon :-
1. Non-intersecting Edges
2. Convex Angles

## Approach
## 1. Genetic Algorithm:

### Initialization: 
Create an initial population of polygons, each represented by a set of vertices in n dimensions. Initial vertices can be generated randomly or based on certain criteria.
### Evaluation: 
Define a fitness function that assesses how well a polygon meets the constraints. Higher fitness indicates better adherence to constraints.
### Selection: 
Select parent polygons based on their fitness scores. Higher fitness polygons are more likely to be selected as parents.
### Crossover: 
Combine vertices of parent polygons to create offspring polygons. Crossover could involve swapping vertices or performing more complex operations based on problem requirements.
### Mutation: 
Introduce small changes to vertices to maintain diversity. Mutation rates determine the probability of changes.
### Replacement: 
Replace the old population with the new offspring population.
### Termination: 
Repeat selection, crossover, and mutation for a specified number of generations or until a satisfactory solution is found.

## 2. Constraint Satisfaction Problem (CSP):

  ### Modeling Constraints:
  Define geometric constraints for non-intersecting, convex polygons. Constraints include angles, side lengths, and bounding box dimensions.
  ### Search Space: 
  The search space consists of all possible sets of vertices that define a polygon. CSP techniques narrow down this space by enforcing constraints.
  ### Backtracking or Propagation: 
  Use CSP strategies to efficiently explore the search space. Backtracking and constraint propagation help identify valid solutions.
  
![output](https://github.com/MuhammadSaqib001/Polygon-Generation-using-Genetic-Algorithm-and-CSP-in-Python/blob/main/sample_output.png)




