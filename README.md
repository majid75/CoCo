# CoCo
A Cooperative Coordination Solver for Traveling Thief Problems

This README file is part of CoCo TTP solver released under the New BSD license. 
CoCo is a cooperative coordination solver developed in C and C++ languages for 
travelling thief problems (TTP). It uses the Linkern tool from the Concorde TSP 
solver in an embedded form to generate initial TSP tours. 

To automatically compile the code, run "./compile.sh" command in the command-line
or manually follow the instructions inside the compile.sh file. After compilation, 
the generated runnable CoCo file can be used for solving TTP instances.

To solve a TTP instance, e.g. "a280_n279_bounded-strongly-corr_01.ttp" located in 
"data/a280-ttp/" subdirectory with 600 seconds as the timeout run the following 
command:

$ ./CoCo a280_n279_bounded-strongly-corr_01 600

More TTP benchmark instances can be accessed in the following address:

https://cs.adelaide.edu.au/~optlog/CEC2014COMP_InstancesNew/



