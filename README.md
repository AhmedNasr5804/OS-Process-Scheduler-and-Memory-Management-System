# OS Process Scheduler and Memory Management System  

## Overview  
This project simulates an operating system's process scheduling and memory management functionalities. Built using C in a Linux environment (Manjaro Linux), the program processes a set of tasks and provides performance statistics, including CPU utilization and average weighted turnaround time.  

## Key Features  
1. **Scheduling Algorithms**:  
   - **Round Robin (RR)**  
   - **Shortest Job First (SJF)**  
   - **Highest Priority First (HPF)**  

2. **Dynamic Memory Management**:  
   - Implements a **smart buddy system** for efficient memory allocation and deallocation.  

3. **Input and Output**:  
   - Accepts a `.txt` input file with process details:  
     ```plaintext
     <Process ID> <Runtime> <Priority> <Memory Size>
     ```  
   - Generates the following output files:  
     - **Memory Log (.log)**: Tracks memory changes.  
     - **Process Log (.log)**: Logs process execution details.  
     - **Performance File (.perf)**: Summarizes system performance.  
