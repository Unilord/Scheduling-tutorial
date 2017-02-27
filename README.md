# Scheduling-tutorial
*An introduction to Multiprocessor and real time scheduling*

# Multiprocessor scheduling

## What do we study when we say multiprocessor scheduling :
- Issues raised by the availablity of more than one processor.
- Scheduling of processes on a multiprocessor system.
- Different design considerations for multiprocessor thread scheduling.

When a computer system contains more than a single processor, several new issues are introduced into the design of the scheduling  function.We begin with a brief overview of multiprocessors:  
1. __Loosely coupled or distributed multiprocessor, or  cluster:__ Consists of a collection of relatively autonomous systems, each processor having its own main memory and I/O channels. 
2. __Functionally  specialized  processors:__ An example is an I/O  processor. In this case, there is a master, general purpose processor; specialized processors are controlled by the master processor and provide services to it.
3. __Tightly  coupled  multiprocessor:__ Consists of a set of processors that share a common main memory and are under the integrated control of an operating system.   

*Our concern is to study the last kind.*
