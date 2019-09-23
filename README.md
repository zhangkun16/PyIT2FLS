PyIT2FLS
========
NumPy based toolkit for Interval Type 2 Fuzzy Logic Systems (IT2FLS) simulation.

## Examples
There are five examples provided along with the toolkit which are as below:
* Ex1: Defining an Interval Type 2 Fuzzy Set (IT2FS)
* Ex2: Application of join and meet operators and plotting the outputs
* Ex3: Defining a simple IT2FLS
* Ex4: Prediction of the Mackey-Glass chaotic time series with PSO-based parameter tuning
* Ex5: Designing Interval Type 2 Fuzzy PID (IT2FPID) controller for a time-delay linear system

In the 4th example, the chaotic Mackey-Glass time series is predicted using PyIT2FLS toolkit. The designed IT2FLS has three inputs and an output. Inputs are three consecutive samples of the time series. For each input and for the ouput three IT2FSs are defined. The parameters of these sets are achieved using the Particle Swarm Optimization (PSO) algorithm to have minimum Mean Square Error (MSE). The full code of the example and the PSO solver are presented in examples folder. The output of the prediction would be as shown below:

<img src="/examples/mackey_glass.jpg" width="400">

The input sets defined and used in 5th example are shown below:

<img src="/examples/delay_pid_input_sets.jpg" width="400">

See the article <PyIT2FLS: A New Python Toolkit for Interval Type 2 Fuzzy Logic Systems> for more information.

## Licence
PyIT2FLS is published under GNU General Public License v3.0. If you are using the developed toolkit, please cite the paper <PyIT2FLS: A New Python Toolkit for Interval Type 2 Fuzzy Logic Systems>.

## Installation
PyIT2FLS can be installed by unzipping the source code in one directory and using this command:

    (sudo) python setup.py install

