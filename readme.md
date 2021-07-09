# exercise#1

## my script

<img width="1216" alt="e1script" src="https://user-images.githubusercontent.com/84737897/125124382-96e59080-e0bd-11eb-8c97-1c4eef348d8d.png">


## test board.c
<img width="1220" alt="e1board" src="https://user-images.githubusercontent.com/84737897/125124319-81706680-e0bd-11eb-8111-6b5ee636f1de.png">


## test pi.c

<img width="1209" alt="e1pi" src="https://user-images.githubusercontent.com/84737897/125124412-a533ac80-e0bd-11eb-8e2b-30e3ff6ab53d.png">

## explaination:
for board.c, the state changes from 1 to 0 for the most case, when pid =38627, the state doesn't change.
after exit, the state of process with pid 38627 changed from 64 to 0.
 for pi.c, the most case changed from 1 to 0 again, pid 38658 remain the state 0, since pid changed from 38658 to 38656.
 after exit, the most case of state changed from 1 to 0 or 2 to 0.
 
 from my output, i can see that there is no much difference in terms of state changes between board.c and pi.c, because for the most process,
 the state changed from 1 to 0. it means that the state will be changed if the process was switched off.
 
 # exercise#2
 
 ## test board.c
 <img width="697" alt="e2board" src="https://user-images.githubusercontent.com/84737897/125126403-aa462b00-e0c0-11eb-863a-eceebd9fb3ef.png">
 
## test pi.c
<img width="682" alt="e2pi" src="https://user-images.githubusercontent.com/84737897/125126423-b4682980-e0c0-11eb-923b-4794886fe529.png">

## test schedtimes.stp
<img width="751" alt="e2sche1" src="https://user-images.githubusercontent.com/84737897/125126457-bfbb5500-e0c0-11eb-9801-651090acb527.png">

## explaination

what i have on exercise#1 is i displayed execname, pid, state, cpu and task, by testing the schedtimes.stp, it got execname, pid, run, sleep, iowait,
queued and total.
since it had more informtion than mine script, and it arranges each group of data vertically, so user can intuitively see the changes of each group of data
corresponding to different process, and the data statistics are more clear.




