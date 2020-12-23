This is the handout directory for the CS:APP Cache Lab. 

========================
Running the autograders:
========================

Before running the autograders, compile your code:
```
    linux> make
```

Check the correctness of your simulator:
```
    linux> ./test-csim
```
Check the correctness and performance of your transpose functions:
 ```
    linux> ./test-trans -M 32 -N 32
    linux> ./test-trans -M 64 -N 64
    linux> ./test-trans -M 61 -N 67
```

Check everything at once (this is the program that your instructor runs):
```
    linux> ./driver.py    
```
=============
Files:
=============

# You will modifying and handing in these two files
csim.c       Your cache simulator</br>
trans.c      Your transpose function</br>

# Tools for evaluating your simulator and transpose function
Makefile     Builds the simulator and tools</br>
README       This file</br>
driver.py*   The driver program, runs test-csim and test-trans</br>
cachelab.c   Required helper functions</br>
cachelab.h   Required header file</br>
csim-ref*    The executable reference cache simulator</br>
test-csim*   Tests your cache simulator</br>
test-trans.c Tests your transpose function</br>
tracegen.c   Helper program used by test-trans</br>
traces/      Trace files used by test-csim.c</br>
