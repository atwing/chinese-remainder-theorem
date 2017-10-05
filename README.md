# Chinese Remainder Theorem implementation in Java

Code computes for every set of integers _a_<sub>_i_</sub>  and set of moduli _n_<sub>_i_</sub> a unqiue integer _x_, such that _x_ &equiv; _a_<sub>_i_</sub> (mod _n_<sub>_i_</sub>) for _i = 1,2,3,...,k_.  
The following conditions must be met:  
- All _n_<sub>_i_</sub> must be pairwise coprime and greater 1.  
- For every _i_, the integers _a_<sub>_i_</sub> with 0 &le; _a_<sub>_i_</sub> < _n_<sub>_i_</sub> have one and only one integer _x_ for which the previously stated congruences hold true.

#### Input
In each line: one integer _k_ for the number of moduli, followed by _k_ pairwise coprime moduli _n_<sub>_1_</sub>,...,_n_<sub>_k_</sub> and _k_ integers _a_<sub>_1_</sub>,...,_a_<sub>_k_</sub>

#### Output
The output contains, for each line in the input, a unique interger _x_ &equiv; _a_<sub>_i_</sub> (mod _n_<sub>_i_</sub>) for _i = 1,2,3,...,k_.


## Example files:
- crt_sample.in &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// input file
- crt_sample.out &nbsp;&nbsp;&nbsp;&nbsp;// output for the example