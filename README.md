# quantum_maxcut
Jupyter notebook for quantum algorithm for the maximum cut problem.

This notebook is still under active development.
Paper reference to follow.

How to use the notebook:
1. Input a list of edges into the code body at the indicated position. 
2. Hit "Run" to execute the algorithm and print the output. 

Note: 
You may need to adjust the variable t in the CNOT gate. It is currently set to the highest possible value indicating that we expect the highest possible cut. So, if your output is not producing two spikes (= a maxcut was found), t should be decreased and the code executed again. Repeat this procedure till the maxcut is found.

You may also need to adjust the variable R used for calculating the number of algorithm iterations. It is currently set to 2 as we expect a single max-cut. If you expect there might be more than one, try setting this value to 2 * expected_number_of_maxcuts.
