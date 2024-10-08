# Exploring Different Encoding and Distance Metrics for a Quantum Instance-based Classifier

The repository contains the code to reproduce the experiments presented in *Exploring Different Encoding and Distance Metrics for a Quantum Instance-based Classifier (Berti, A., Bernasconi, A., Del Corso, G. M., & Guidotti, R.*)

The repository is organized in three main directories:
<ol>
    <li> _knn_. It contains the implementations of Amplitude-based QKNN and Basis-based QKNN </li>
    <li> _test_launchers_. It contains the scripts to run the entire set of tests performed </li>
    <li> _utility_. It contains some utilities needed to store the results, encode data into its binary representation and transform data according to amplitude and basis encodings</li>
</ol>

##  :runner: How to run experiments

The scripts for experiments are located in the *test_launchers* directory and are the followings:
<ol>
    <li> amplitude_launch_tests.py </li>
    <li> amplitude_digits_launch_tests.py </li>
    <li> basis_launch_tests.py </li>
    <li> basis_two_digits_launch_tests.py </li>
    <li> two_digits_launch_tests.py </li>
</ol>

Follows an example to run the experiments:

_Move to the main directory (/*quantum_knn*) and run:_

`python3 ./test_launchers/amplitude_launch_tests.py`
