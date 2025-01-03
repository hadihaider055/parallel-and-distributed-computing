# Parallel-and-Distributed-Computing

Welcome to my **Parallel and Distributed Computing** repository! This repository serves as a learning hub where I explore various fundamental and advanced concepts in parallelism, concurrency, and distributed computing through Python. It is part of my course on Parallel and Distributed Computing and contains various code samples, exercises, and projects related to these topics.

---

## 🚀 Overview

This repository showcases several projects and exercises that illustrate the core principles of parallel and distributed computing. Whether you're a beginner or looking to delve into more complex topics, this repository provides hands-on experience with multithreading, multiprocessing, distributed systems, and concurrent execution.

---

# 📁 Repository Structure

## 📜 Basic Programs
- **Basics:** 
  Contains simple programs that cover basic concepts such as functions, classes, and data structures. It's your starting point to understand the building blocks before diving into more complex topics.


- **`calculator.py`:**  
  A simple command-line calculator that demonstrates basic user input and arithmetic operations. A great start for understanding how to handle user inputs and perform operations.

- **`basics.py`:**  
  A file that covers basic Python data structures like lists, tuples, and dictionaries. Perfect for beginners looking to understand how data is managed in Python.

- **`greeting.py`:**  
  An example of a Python function that greets the user. It demonstrates how to define and call functions, an essential concept in programming.

- **`object.py`:**  
  A class-based example that shows how to create and use Python classes and objects. This helps in understanding object-oriented programming, a core concept in many computing applications.
---
## 📜 Chapters
  These folders contain exercises and programs from various chapters in my course. As the course progresses, new chapters will be added to reflect more advanced topics in parallel and distributed computing.
  - **Chapter 1: Multithreading Tasks**  
    This chapter focuses on foundational multithreading concepts and practical implementations using Python. It includes the following tasks:
    
    1. **Multiprocessing and Multithreading Performance Comparison:**  
       - Compares the execution time of processing a large dataset using Python's multiprocessing and threading modules.  
       - Implements `do_something` to distribute tasks across multiple processes or threads.  
       - Example Output:  
         ```plaintext
         List processing complete.
         Multiprocessing time = 1.23 seconds
         List processing complete.
         Multithreading time = 0.89 seconds
         ```

    2. **Fibonacci Calculation with Threads:**  
       - Spawns multiple threads to calculate the Fibonacci sequence.  
       - Demonstrates task parallelism using Python's `threading` module.  
       - Example Output:  
         ```plaintext
         Starting thread 1
         Starting thread 2
         Starting thread 3
         Total execution time: 3.56 seconds
         ```

    3. **Data Parallelism with NumPy:**  
       - Uses NumPy for efficient vector addition on large datasets.  
       - Leverages NumPy's internal parallelization for optimized computation.  
       - Example Output:  
         ```plaintext
         Time taken for data parallel computation (NumPy): 0.01234 seconds
         First 10 elements of result: [1.23, 2.34, 3.45, ...]
         ```

    4. **ThreadPoolExecutor for Task Scheduling:**  
       - Implements a task scheduler using Python's `concurrent.futures.ThreadPoolExecutor`.  
       - Schedules and executes multiple tasks concurrently.  
       - Example Output:  
         ```plaintext
         Task 1 executed
         Task 2 executed
         ```
## 🛠️ Key Features and Learning Outcomes

- **Concurrency and Parallelism:**  
  Learn how to perform multiple tasks simultaneously in Python using threads and processes, making efficient use of system resources.

- **Threading and Multiprocessing:**  
  Understand the concepts of multithreading and multiprocessing, and how Python can manage concurrent execution to speed up tasks.

- **Distributed Computing:**  
  Gain a foundational understanding of how distributed systems work and how tasks can be split across multiple machines.

---

## 💡 Future Work

- **Advanced Parallel Algorithms:**  
  Explore parallel sorting, searching, and matrix multiplication algorithms.

- **Distributed Systems:**  
  Develop projects simulating distributed systems with message-passing techniques across virtual machines.

- **Optimization:**  
  Techniques for optimizing performance in both single-machine and distributed environments.

---

## 🚀 How to Run the Code

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/Parallel-and-Distributed-Computing.git

    Navigate to any program in the repository.

    Make sure you have Python installed (version 3.x recommended).

    Run the Python file:

python filename.py
