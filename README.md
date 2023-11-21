# Optimized-a-python-based-LP-model-using-Pulp

The linear programming model developed in Python using the PuLP library addresses the coal shipping problem for the Willow Run Coal Company. The model aims to minimize the total cost of shipping coal from three mines to four utility power plants along the East Coast. Decision variables represent the amount of coal to be shipped from each mine to each plant. The objective is to minimize the total cost, including mining and processing costs and shipping costs.

Constraints include mine capacity limitations, plant demand requirements, and constraints on the ash and sulfur content of the coal received by each plant. The Python script uses PuLP to formulate the problem, set up the objective function and constraints, and solve the linear programming model. The results provide the optimal amount of coal to be shipped from each mine to each plant, minimizing the total cost while satisfying all constraints.

•Model:	The Willow Run Coal Company operates three times minus in Kentucky and West Virginia and supplies coal to four utility power plants along the East Coast. The cost of shipping coal from each mine to each plant, the capacity at each of the fours mines and demand at each plants are shown in the table:
Mine          Plant1       Plant2       Plant3          Plant4               Mine Capacity (Tons)
1                     7                  9                10                12                            220
2                      9                 7                 8                  12                            190
3                      11               14                5                   7                             280
Demands       110            160               90                180                   
(tons)
The Cost of mining and processing coal is 62$ per ton in Mine1, 67 in mine 2 and 75 in mine 3.
The percentage of ash and sulfur per ton of coal at each mine is as follows:
Mine       Ash%          Sulfur% 
1               9                 6
2               5                 4
3               4                 3
Each Plant has different cleaning equipment. Plant 1 requires that the coal it receives can have no more than 6% ash and 5% sulfur; plant 2 can have no more than 5% ash and sulfur combined; plant 3 can have no more than 5% ash and 7% sulfur and plant 4 coal can have no more than 6% ash and sulfur combined. The company wants to determine the amount of coal to produce at each mine and ship to it’s customers that will minimize its total cost.
 

