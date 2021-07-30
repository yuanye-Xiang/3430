# lab3
## ex 1

## change of stp file
<img width="1031" alt="change of stp file" src="https://user-images.githubusercontent.com/84737897/127698437-1dab3be6-c3ac-4913-a0ea-9cc4d31848c3.png">

## change of program
<img width="885" alt="chnge of program" src="https://user-images.githubusercontent.com/84737897/127698471-28153933-f74c-4992-8792-3272889047cf.png">

## output
<img width="623" alt="output" src="https://user-images.githubusercontent.com/84737897/127698512-a8a82e18-f6ac-433e-a47b-c74f54f929f5.png">

## gdb command
<img width="539" alt="gdb output" src="https://user-images.githubusercontent.com/84737897/127698554-11cb4dd4-746a-4599-a39c-dfbe4d53844a.png">

## q1
it takes me to find the name of those 3 lock variable that are shown on the pic of gdb command above

## q2
pool_workcv has the most contention
because it's the first lock for multiple thread in thread_madness file, so it shuold be contended by them at the first time. Also, it can protect the data away
from the process of contention.

## q3             
 
1. pool_workcv  wait time:7917 * 657 = 5201469        2. pool_waitcv wait time: 1 * 7365 = 7365          3. pool_busycv  wait time: 1 * 138 = 138  

## q4
## waiting time for 8 cores
<img width="679" alt="截屏2021-07-30 下午2 25 18" src="https://user-images.githubusercontent.com/84737897/127702769-e9666d3e-dd74-406a-be16-cb42cec30f97.png">

## waiting time for 4 cores
<img width="668" alt="截屏2021-07-30 下午2 28 53" src="https://user-images.githubusercontent.com/84737897/127702823-4c2e5470-13a7-40dd-a08a-9851157fa1d5.png">

so after calculation, total waiting time for 1 core is 5208972, total waiting time for 4 cores is 4701713, and total waiting time for 8 cores is 4633553. We can
see the total waiting time is decreasing by increasing the number of cores.
