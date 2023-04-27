This project aims to design a scheduling program that implements a queue with two levels: fixed priority preemptive scheduling and shortest remaining time first scheduling. The program will have two queues, with the higher priority processes in Queue 1 and lower priority processes in Queue 2.

The fixed priority preemptive scheduling algorithm works by assigning each process a priority level, with the highest priority being 0. If a process with a higher priority arrives while another process is running, the running process is preempted, and the higher priority process is executed. If a process in Queue 1 completes its execution, the next process in Queue 1 is executed.

If a process from Queue 1 is preempted, it is moved to Queue 2, where the shortest remaining time first (SRTF) algorithm is used to execute the processes. In this algorithm, the process with the shortest remaining execution time is executed first.

The program should be designed in such a way that the time for which a process strictly executes should be considered in multiples of 2, and Queue 2 should be processed only after Queue 1 becomes empty. Finally, the priority of Queue 2 should be lower than that of Queue 1.
