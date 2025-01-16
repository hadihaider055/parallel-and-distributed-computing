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

### 🛠️ Key Topics Covered:

- Basic programming concepts such as functions, data structures, and classes.
- Object-oriented programming (OOP) in Python.
- Advanced parallel computing techniques, including the use of multiprocessing, threading, and GPU.
- Inter-process communication methods and synchronization techniques for multi-core and multi-threaded environments.
- Asynchronous programming with asyncio and concurrent futures.

## 📜 Script Descriptions

### 1. **calculator.py**

A simple calculator program that allows users to perform basic arithmetic operations:

- Addition
- Subtraction
- Multiplication
- Division  
  Users input two numbers and select the operation to get the result.

### 2. **data_structures.py**

This script provides examples of Python's core data structures, including:

- Tuples
- Lists
- Dictionaries  
  You will learn how to use them effectively in various scenarios.

### 3. **functions.py**

A guide to creating and using functions in Python, including:

- Function definitions
- Parameters and return values
- Calling functions with different arguments

### 4. **classes.py**

Introduces object-oriented programming (OOP) in Python:

- Defining classes and creating objects
- Writing methods
- Demonstrating inheritance to reuse and extend code

### 5. **mpi_example.py**

Explains how to perform distributed computing using the **MPI** library (`mpi4py`):

- Sending and receiving messages between processes
- Understanding process ranks and sizes in MPI contexts

### 6. **multiprocessing_vs_threading.py**

A comparative script that explains the differences between multiprocessing and threading:

- **Multiprocessing**: Runs tasks in separate processes to utilize multiple CPUs.
- **Multithreading**: Shares memory space between threads for concurrent execution.  
  Performance differences are analyzed through a basic list-processing task.

### 7. **gpu_computation.py**

Showcases how to accelerate computations using **Numba's CUDA JIT**:

- Implements vector addition on a GPU for performance gains.
- Includes result validation using Numba’s CUDA functionality.

### 8. **num_parallel_computing.py**

Demonstrates data parallelism with **NumPy**:

- Performs vector addition using NumPy’s optimized array operations.
- Measures execution times for large-scale computations.

### 9. **threadpool_executor.py**

Explores task parallelism using `ThreadPoolExecutor`:

- Manages a pool of threads to execute functions concurrently.
- Executes tasks asynchronously, simplifying thread management.

### 10. **producer_consumer.py**

Illustrates the classic producer-consumer problem using Python's **multiprocessing** module:

- A `producer` generates items and adds them to a shared queue.
- A `consumer` retrieves and processes items from the queue.

### 11. **semaphore_example.py**

Demonstrates the use of **semaphores** in threading to limit access to shared resources:

- Controls the number of threads accessing a resource concurrently.

### 12. **multiprocessing_example.py**

Explains the basics of Python’s **multiprocessing** module:

- Runs two separate functions (e.g., square and cube calculations) in parallel.
- Includes process synchronization and joining.

### 13. **fibonacci_threading.py**

Calculates Fibonacci numbers using **multithreading**:

- Distributes computation across multiple threads to improve efficiency.

### 14. **threading_event_example.py**

Uses threading events for inter-thread communication:

- A producer thread generates random numbers.
- A consumer thread processes them, synchronized using an event.

### 15. **lock_example.py**

Explains the use of thread locks for synchronization:

- Prevents race conditions by ensuring only one thread accesses a shared resource at a time.

### 16. **Process-Based Parallelism**

In this chapter, we cover advanced multiprocessing techniques, including:

- **communicatingWithPipe**: Inter-process communication using pipes for data exchange.
- **communicatingWithQueue**: Sharing data between processes using a thread-safe queue.
- **killingProcesses**: Terminating processes gracefully.
- **namingProcess**: Assigning names to processes for easier identification.
- **runBackgroundProcesses**: Running processes in the background while the main program continues.
- **spawningProcess**: Spawning new processes dynamically to execute tasks concurrently.

### 17. **Message Passing**

Chapter 5 focuses on message-passing techniques to enable efficient communication between processes, including:

- **broadcast**: Sending messages from one process to all other processes simultaneously.
- **deadLockProblems**: Understanding and preventing deadlocks when multiple processes are waiting for resources.
- **pointToPointCommunication**: Facilitating communication between two specific processes.
- **gather**: Collecting data from multiple processes into one process.
- **scatter**: Distributing data from one process to multiple processes.

### 18. **Asynchronous Programming**

Chapter 6 covers asynchronous programming using Python’s `asyncio` library and `concurrent.futures`. Key topics include:

- **asyncioAndFuture**: Using `asyncio` in conjunction with `Future` objects to manage asynchronous tasks and future results.
- **asyncioCoroutine**: Implementing coroutines to execute asynchronous tasks concurrently.
- **asyncioEventLoop**: Understanding the role of the event loop in managing asynchronous tasks.
- **concurrent_futures_pooling**: Utilizing `concurrent.futures` to manage a pool of threads or processes for asynchronous task execution.

## 📜 Chapters

These folders contain exercises and programs from various chapters in my course. As the course progresses, new chapters will be added to reflect more advanced topics in parallel and distributed computing.

- **Chapter 1**
- **Chapter 2**
- **Chapter 3**
- **Chapter 4**
- **Chapter 5**
- **Chapter 6**
- **Chapter 7**
- **Chapter 8**
- **Chapter 9**
- **Chapter 10**

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
   ```
