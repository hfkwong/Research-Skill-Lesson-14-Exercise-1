# Readme (Sort)

This package contains all source codes for
1. Sort

Usage Step
==========
a. Compilation
    gcc sort.c -o run

b. Execution
    ./run

c. Input Files
   1. By default, we have file "config.txt" for configuration
   2. Data file (filename is specified in "config.txt")

d. Output Files
   1. "output.txt" which contains the sorted list
   2. "stat.txt" which captures the number of swaps
   3. "time.txt" which captures the time statistics of the program


Appendix A. Format of Configure file (By default, the configure file is named as "config.txt")
------------------------------------

1. data file (e.g., data.txt)
2. size of the data set
3. parameter2
4. parameter3
5. parameter4


Appendix B. Format of data file
------------------------------------------
Each integer corresponds to a data point.

The format is:

    <int 1> <int 2> ... <int n>



Appendix C. Format of "output.txt"
------------------------------------------
Each integer corresponds to a sorted data point.

The format is:

    <sorted int 1> <sorted int 2> ... <sorted int n>


Appendix D. Format of "stat.txt"
------------------------------------------
A single line containing the total number of swaps

1. number of swaps



Appendix E. Format of "time.txt"
------------------------------------------
Each line corresponds to a user time and system time
1. time for reading the config and data files
2. time for sorting
3. time for writing the sorted output (and stat file)
4. time for the whole program

