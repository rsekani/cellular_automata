# Cellular Automata Summer School 2023
The research project for the Cellular automata summer school on using CA techniqiues for optimization problems..


TSP Genetic algorithm CA
	No elistist strategy
	No Simulated annealing
	problem - only 50 % of cells are alive and so we don't do anything, we will keep the rest of population without doing anything
	We dont do this (compare whether the mutated child fitness > the current cells one and only when this conditions is true we replace)
	Tested Rule 2 and 3 with NULL boundary conditions
	
TSA with GA CA Elitist
	No simulated annealing
	No elistist strategy
	Since 50% of cells are alive, we randomly select from the same set t make it 100%
	We compare whether the mutated child fitness > the current cells one and only when this conditions is true we replace
	we have set the random seed to be 0
	
TSA with GA CA Elitist one padded
	No simulated annealing
	No elistist strategy
	PAD WITH 1 CONSTANT
	Since 50% of cells are alive, we randomly select from the same set t make it 100%
	We compare whether the mutated child fitness > the current cells one and only when this conditions is true we replace
	we have set the random seed to be 0
	
TSA with GA CA Elitist periodic config
	No simulated annealing
	No elistist strategy
	PAD WITH WRAP (PERIODIC PADDING)
	Since 50% of cells are alive, we randomly select from the same set t make it 100%
	We compare whether the mutated child fitness > the current cells one and only when this conditions is true we replace
	we have set the random seed to be 0
	
	
Rule 3TSA with GA CA Elitist
	No simulated annealing
	No elistist strategy
	Constant 0 padding
	RULE 3
	Since 50% of cells are alive, we randomly select from the same set t make it 100%
	We compare whether the mutated child fitness > the current cells one and only when this conditions is true we replace
	we have set the random seed to be 0
	
Non Uniform CA_RuleTSA with GA CA Elitist
	No simulated annealing
	No elistist strategy
	Constant 0 padding
	NON UNIFORM RULE
	Since 50% of cells are alive, we randomly select from the same set t make it 100%
	We compare whether the mutated child fitness > the current cells one and only when this conditions is true we replace
	we have set the random seed to be 0
	
TSP GA CA Comparison
	Comparison GA, Hybrid CA rule 2 and Non uniform CA
