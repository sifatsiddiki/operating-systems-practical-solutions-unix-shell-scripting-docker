# operating-systems-practical-solutions-unix-shell-scripting-docker
Practical implementations for Operating Systems (ENUIC) course, covering UNIX Shell Scripting, CPU Scheduling analysis using simulators, and containerized environments with Docker.
# Operating Systems (ENUIC) - Practical Final Paper

This repository contains the complete practical solutions and documentation submitted for the **Operating Systems (ENUIC)** course (Module: **ENI08108**) at Edinburgh Napier University.

##  Project Overview
The project showcases hands-on proficiency in core operating system principles, ranging from low-level automation via UNIX command line tools to structural testing inside containerized environments using Docker.

##  Key Tasks & Implementations

### Task 1: Scripting in a UNIX CLI
* **Objective:** Automating word occurrence and evaluation across multiple text inputs.
* **Key Scripts:** 
  * `count.sh`: A dynamic Bash shell script utilizing sequential `grep` search mechanics coupled with line-count utilities (`wc -l`) to track string patterns in distinct directory workflows.
* **Environment:** Developed and validated via a remote terminal structure (`vsoc2.napier.ac.uk`) using the native `vi` text editor.

### Task 2: CPU Scheduling Analysis
* **Objective:** Evaluating process orchestration constraints across multiple structural execution strategies.
* **Simulator:** Explored performance metrics utilizing the **CPU-OS (02) Simulator**.
* **Algorithms Analyzed:**
  * **First-Come-First-Served (FCFS):** Evaluated baseline queuing behaviors.
  * **Shortest-Job-First (SJF):** Analyzed process priority mechanics based on burst duration.
  * **Round Robin (RR):** Benchmarked preemption behaviors using explicit 0.2-second static context cycles.
* **Metrics Tracked:** Process states, individual ready queues, average process waiting times, and total turnarounds.

### Task 3: Bash Scripting with Docker Containers
* **Objective:** Building reproducible application testbeds through container virtualization frameworks.
* **Automation:** Developed automated script sequences (`sifu.sh`) executed inside custom micro-environments.
* **Workflow:**
  * Pulled stable base images (`ubuntu:latest`) via Docker engine protocols.
  * Isolated testing environments into dedicated running instances (`sifu-container`).
  * Managed iterative code writing and environment links seamlessly using VS Code.

##  Academic Context
* **Module Code:** ENI08108 (2024-5 TR1 001)
* **Module Leader:** Athira Chitrapal
* **Student Identifier:** 40735842
* **Submission Date:** December 9, 2024

---
*Disclaimer: This repository is intended strictly for portfolio display and academic documentation purposes. All structural works align with academic integrity guidelines.*
