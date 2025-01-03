# Chapter 1: Multithreading Tasks
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