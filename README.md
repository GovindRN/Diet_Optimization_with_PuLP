# Diet Optimizing Project
This GitHub repository will be used to host project files for Diet Optimizing using PuLP.

The problem statement that we are trying to solve is to come up with a diet plan that includes food that provide maximum required nutrients for a person with minimal cost.

The goal of this project is to implement **Optimization using PuLP** python library. 

## Optimization using PuLP
PuLP is an Linear Programming modeler in Python. A Linear Programming problem is where we are given multiple equations. The value of one of the equations has to be maximized or minimized while the other equations are constraints. Linear Programming is used to solve Optimization problems given a few constraints.

## Implementation at high level

 - Load the data set
	 - Data set includes different food items along with their serving size, cost and amount of various nutrients present in it
 - For the selected food items, calculate the total cost of diet plan and serving size of each food for various constraints
	 - Iteration#1 - Constraints  
		 - maximum and minimum values of nutrients per day
	 - Iteration#2 - Constraints
		 - non-negative and non-zero food intake value 
		 - minimum and maximum serving size provider for each food
		 - at most only one of Celery or Frozen Broccoli should be selected
		 - total number of food items selected which belong to one of meat/poultry/fish/eggs must be at least 3
