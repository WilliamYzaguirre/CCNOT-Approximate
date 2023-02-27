CNNOT Approximate
The point of this project is to see how closely we can approximate the CCNOT gate using at most four 2-qubit gates.
I first attempt to solve this by parameterizing the four 2-qubit unitaries with 45 parameters, and then using the grey wolf and particle swarm optimization algorithms to optimize these parameters.
I then switch to using a partial decomposition for the CCNOT gate, with a few single qubit unitaries with 3 parameters each, and optimizing those.
I used the Hilbert-Schmidt distance as the loss the function, to evaluate how close my circuit/unitary is to CCNOT.