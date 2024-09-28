<img src="https://skillicons.dev/icons?i=java" />
<br> 

# CPU Scheduler
CPU Scheduler is a simulation project designed to demonstrate how different CPU scheduling algorithms work in an operating system. This project provides an interactive and visual approach to understanding how various scheduling strategies allocate CPU time to processes in a multi-tasking environment.

## Table of Contents
1. Overview
2. Features
3. Installation
4. Usage
5. Supported Algorithms
6. Contributing
7. License
   
## Overview
The CPU Scheduler project simulates various CPU scheduling algorithms such as First-Come-First-Serve (FCFS), Shortest Job Next (SJN), Round Robin (RR), and Priority Scheduling. The project helps students and developers visualize how processes are scheduled and how different strategies affect process execution times and CPU utilization.

The scheduler takes multiple processes as input, each with its arrival time, burst time, and priority (if applicable), and displays a Gantt chart representing the execution order.

## Features
Simulates multiple CPU scheduling algorithms: Supports common CPU scheduling algorithms.

Gantt chart visualization: Provides a visual representation of how processes are scheduled.

Detailed statistics: Displays key metrics such as turnaround time, waiting time, and CPU utilization.

User-friendly interface: Simple interface for inputting processes and scheduling parameters.

## Installation
To set up and run the CPU Scheduler on your local machine:

1. Clone the repository: ```git clone https://github.com/joeshwoa/CPU_Scheduler.git```
2. Navigate into the project directory: ```cd CPU_Scheduler```
3. Run the application

## Usage
Input Process Information: Add the process details like arrival time, burst time, and priority (if using priority scheduling).

Select Scheduling Algorithm: Choose the scheduling algorithm you want to simulate.

Run Simulation: The project will display the Gantt chart and output important statistics such as:
Turnaround Time
Waiting Time
Response Time

Analyze Results: Compare how different algorithms affect the process execution and CPU efficiency.

## Supported Algorithms
The CPU Scheduler project supports the following algorithms:

First-Come-First-Serve (FCFS): The simplest form of scheduling where the process that arrives first is executed first.

Shortest Job Next (SJN): Prioritizes processes with the shortest burst time.

Round Robin (RR): Each process is assigned a fixed time slice (quantum), rotating between all processes.

Priority Scheduling: Processes are scheduled based on priority levels.

Shortest Remaining Time First (SRTF): A preemptive version of SJN that switches between processes based on the remaining burst time.

## Contributing
We welcome contributions to improve the CPU Scheduler. To contribute:

1. Fork the repository.
2. Create a new branch: ```git checkout -b feature-name```.
3. Make your changes and commit them: ```git commit -m 'Add new feature'```.
4. Push to the branch: ```git push origin feature-name```.
5. Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
