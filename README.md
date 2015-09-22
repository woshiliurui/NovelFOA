# NovelFOA
Compare the performance of GA, DE, FOA, and our proposed FOA (Using the joint replenishment problem (JRP))

# Main function
Main Function.m: The main function of this comparison.
Input.m and input_scale.m: Guide parameter input.
Several_Alg.m: Compare several algorithms.

# The proposed FOA 
novel_FOA.m: The proposed FOA to solve the JRPs.
calculate_A_B.m and bound_K.m: Calculate the bound of k.
X_Y_generate.m: Generate new individul.

# Other contrast algorithms: Genetic algorithm (GA), Differential evolution algorithm (DE), and FOA 
GA_SHIYL.m: The GA in [1] to solve the JRPs.
DE_SHIYL.m: The DE in [1] to solve the JRPs.
NFOA_SHIYL.m: The DE in [1] to solve the JRPs.
ComputeKU_SHIYL.m: Calculate the bound of k in DE,GA,and NFOA_SHIYL.
CalculateT: Calculate basic cycle time.
CalculateTC: Calculate Total Cost.
