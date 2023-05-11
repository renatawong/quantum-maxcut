# Quantum maxcut
A quantum algorithm for the maximum cut problem in arbitrary graphs.


# Status
This notebook is complete.


# How to use the notebook:
1. Input a list of edges into the code body at the indicated position. 
2. Hit "Run" to execute the algorithm and print the output. 

Note: If you run the Python version, you will get a dictionary of results as output.

# Note: 
You may need to adjust the variable t in the CNOT gate. It is currently set to the highest possible value indicating that we expect the highest possible cut. So, if your output is not producing two spikes (= a maxcut was found), t should be decreased and the code executed again. Repeat this procedure till the maxcut is found.

You may also need to adjust the variable R used for calculating the number of algorithm iterations. It is currently set to 2 as we expect a single max-cut. If you expect there might be more than one, try setting this value to 2 * expected_number_of_maxcuts.

# Acknowledgement
This code is based on the theory described in [1]. 

The code was written by Renata Wong (https://orcid.org/0000-0001-5468-0716).

This work benefited greatly from discussions with Prof. Weng-Long Chang (National Kaohsiung University of Science and Technology). All remaining deficiencies are my own.

# References
[1] W-L. Chang, R. Wong, W-Y. Chung, Y-H. Chen, J-C. Chen, and A.V. Vasilakos, Quantum speedup for the maximum cut problem, CTHPC 2023  (https://sites.google.com/view/cthpc2023), May 25-26, 2023, National Cheng Kung University, Tainan, Taiwan.
