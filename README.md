# K1563_B40_NIKESHGUPTA
OPERATING SYSTEM PROJECT
Student Name: NIKESH. KUMAR. GUPTA.
Student ID: 11605312.
Section:K1653
Email Address: nikeshgupta212@gmail.com
GitHub Link: https://github.com/NIKESH00/K1563_B40_NIKESHGUPTA
 
Description:
1. Program Description:  SJF (Shortest Job First) Scheduling is the non-preemptive while in these program we will implement it in in preemptive version of SJF also known as the Shortest Remaining Time First(SRTF/SROT).
In these scheduling algorithm, the process with the smallest amount of time remaining until completion is selected to be executed. While the currently executing process is one of the shortest amount of time remaining, and hence that the time should only be reduced as an execution progress. Where the progress will always run till they complete processes either the new process is added that is requiring a smaller amount of time.
Advantages of SJF: 1. Short processes are handled very quickly.
                           2. The system also requires very little time requirement since it only makes a    
                           decision when a process completes or the new process is added to it.
                          3. When the new process is added to the algorithm it only needs to compare it with the currently running/executing process with the new process, ignoring all the other running processes waiting to execute.
Disadvantages of SJF: 1. Similar to the SJF (Shortest Job First) Scheduling algorithm, is having the potential or the ability to process starvation.
                      2. As long as the process may have held off the indefinitely if the shortest process are continually added.
2. Algorithm of SJF: 1. Start the execution/ Starting of the Algorithm.
                  2.Enter the number of the processes you want to allocate.
                  3.Enter the Processes names which you like to set.
                  4.Enter the Arrival Time of the Processes.
                  5.Enter the Burst Time of the processes.
                  6.Finally after entering the input by the user the Completion time is calculated for each of the processes and with the help of it the Turn Around Time is calculated by using the formula (Comletion time-Arrival time).
                  7.Aswellas the Waiting Time is also calculated with the help of the Turn Around Time by using the formula as (Turn Around Time - Burst Time) of the CPU.
                  8.After all these internal Calculation the Average Waiting Time is Calculated by adding all the waiting time values of the processes and dividing it by the number of the processes.
                  9.At last the Average Turn Around Time is calculated by adding all the values obtained by the Turn Around Time divided by the number of the processes.
                  10.Displaying all the processes along with their Gantt Chart.  
                  11.At the end Termination of the program.  
Code Snippet:
 
 
 
 
 
3. Purpose of Use: It is used to calculate the Average waiting Time of the CPU processes and the Average Turn Around Time of the processes. And it tells how the work is done for the processes in the CPU.
4. Test Cases Applied Are: -  output: Shortest Job First for preemptive is as follows: -

Enter the Number of processes you want to allocate: 4
Enter the Arrival Time of the process: p1:0    p2:1    p3:2   p4:4
Enter the Burst Time of the Processes: p1:5    p2:3     p3:3    p4:1
waiting Time (Turn Around Time - Burst Time) :   7:p1   1:p2   3:p3   1:p4
Turn Around Time (Completion Time - Arrival Time):   12:p1    4:p2  6:p3  2:p4

Average Waiting Time for the above output is: 3.00
Average Turn Around Time for the above output is: 6.00
5.Boundary Condition: The boundary condition of the code is that it cannot perform the following operations: -
1.	Similar to the SJF (Shortest Job First) Scheduling algorithm is having the potential or the ability to process starvation.
2.	As long as the process may have held off the indefinitely if the shortest process are continually added
6.Number of Revisions made to the code:
More than 5-times revision is made to the code in the GitHub account
 Yes, I have made the 5 revisions of the solutions in the provided GitHub site.
GitHub Link: - https://github.com/NIKESH00/K1563_B40_NIKESHGUPTA

