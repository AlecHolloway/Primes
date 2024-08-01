# Primes
A concurrent prime sieve program for xv6 using pipes

Goal is to use pipe and fork to set up the pipeline. The first process feeds the numbers 2 through 35 into the pipeline. For each prime number, you will arrange to create one process that reads from its left neighbor over a pipe and writes to its right neighbor over another pipe. Since xv6 has limited number of file descriptors and processes, the first process can stop at 35. 

https://pdos.csail.mit.edu/6.828/2023/labs/util.html

![image](https://github.com/user-attachments/assets/b1dd3cbc-3f88-4512-8456-5617681af195)
![image](https://github.com/user-attachments/assets/8f7ec1e2-e419-461d-806b-174ce59e6809)

