# Chapter 3: Process-Based Parallelism

This chapter explores various concepts and Python implementations related to process management, interprocess communication (IPC), and process synchronization. It covers examples that demonstrate how processes communicate using pipes, queues, and barriers, as well as handling processes in the background, killing processes, and managing process pools.

## 1. **`communicating_with_pipe.py`**  
- Demonstrates interprocess communication using pipes to send data between processes.  
- Example Output:  
  ```plaintext
  Process 1 sending message: Hello from Process 1
  Process 2 received message: Hello from Process 1

2. communicating_with_queue.py

    Demonstrates interprocess communication using queues to exchange data between processes.
    Example Output:
    ```plaintext
    Process 1 added item to queue: Item 1
    Process 2 received item from queue: Item 1

3. derom.py

    Implements a simple program related to process communication or management.
    Example Output:
    ```plaintext
    Derom process executed successfully.

4. killing_processes.py

    Demonstrates how to terminate running processes using Python.
    Example Output:
    ```plaintext
    Process with PID 1234 killed successfully.

5. myFunc.py

    Defines a function or process-related code to be executed by processes.
    Example Output:
    ```plaintext
    Function executed in child process.

6. naming_processes.py

    Demonstrates the naming of processes and how to retrieve process names.
    Example Output:
    ```plaintext
    Process name: Process-1

7. process_in_subclass.py

    Shows how to subclass the Process class to create custom process implementations.
    Example Output:
    ```plaintext
    Custom process subclass executed.

8. process_pool.py

    Implements a process pool for concurrent execution of tasks using the Pool class.
    Example Output:
    ```plaintext
    Process pool task completed.

9. processes_barrier.py

    Demonstrates how to use barriers to synchronize processes and ensure they proceed together.
    Example Output:
    ```plaintext
    All processes reached the barrier.

10. run_background_processes.py

    Demonstrates how to run processes in the background.
    Example Output:
    ```plaintext
    Background process started.

11. run_background_processes_no_daemons.py

    Shows how to run background processes that are not daemonized, meaning they do not exit when the main program ends.
    Example Output:
    ```plaintext
    Non-daemon background process started.

12. spawning_processes.py

    Demonstrates how to spawn new processes and manage their execution.
    Example Output:
    ```plaintext
    Spawning new process with PID 1234

13. spawning_processes_namespace.py

    Demonstrates how to use multiprocessing with a namespace to share data between processes.
    Example Output:
    ```plaintext
    Namespace value: 42


This README file now only contains the Python scripts without the `.txt` entries. You can place this directly into your `README.md` file for GitHub. Let me know if you need further adjustments!
