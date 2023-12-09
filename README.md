# Quantum maxcut
Quantum algorithms for the maximum cut problem in arbitrary graphs.


# Status
This project consists of two notebooks. Both are complete.


# How to use the notebooks:
1. Input a list of edges into the code body at the indicated position. 
2. Hit "Run" to execute the algorithm and print the output. 

Note: If you run the Python version, you will get a dictionary of results as output.

# Note: 
You may need to adjust the variable t in the CNOT gate. It is currently set to the highest possible value indicating that we expect the highest possible cut. So, if your output is not producing two spikes (= a maxcut was found), t should be decreased and the code executed again. Repeat this procedure till the maxcut is found.

You may also need to adjust the variable R used for calculating the number of algorithm iterations. It is currently set to 2 as we expect a single max-cut. If you expect there might be more than one, try setting this value to 2 * expected_number_of_maxcuts.

# Acknowledgement
The code of [quantum_maxcut_algorithm.ipynb](https://github.com/renatawong/quantum-maxcut/blob/5cfe3544b78f365fa78f4d8edba0d7885cbd39e5/quantum_maxcut_algorithm.ipynb) is based on the theory described in [1]. 

The code of [quantum_maxcut_algorithm_optimized.ipynb](https://github.com/renatawong/quantum-maxcut/blob/5063a8e2a4683b8f57b22de3d0d66c6226d398d9/quantum_maxcut_algorithm_optimized.ipynb) is based on the theory described in [2].

The code was written by Renata Wong (https://renatawong.github.io/).

This work benefited greatly from discussions with Prof. Weng-Long Chang (National Kaohsiung University of Science and Technology) and Yu-Hao Chen (National Taiwan University). All remaining deficiencies are my own.

# References
[1] W-L. Chang, R. Wong, W-Y. Chung, Y-H. Chen, J-C. Chen, and A.V. Vasilakos, Quantum speedup for the maximum cut problem, CTHPC 2023  (https://sites.google.com/view/cthpc2023), May 25-26, 2023, Taiwan. DOI: [https://doi.org/10.48550/arXiv.2305.16644](https://doi.org/10.48550/arXiv.2305.16644)

[2] W-L. Chang, R. Wong, Y-H. Chen, W-Y. Chung, J-C. Chen, and A.V. Vasilakos, Bioinspired Quantum Oracle Circuits for Biomolecular Solutions of the Maximum Cut Problem. TechRxiv. December 07, 2023. DOI: [https://doi.org/10.36227/techrxiv.24736389]
