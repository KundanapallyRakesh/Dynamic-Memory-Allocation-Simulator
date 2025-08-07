🧠 Dynamic Memory Allocation Simulator in Java
This is a Java-based simulation of dynamic memory allocation using three widely known strategies: First Fit, Best Fit, and Worst Fit. The program supports runtime operations like allocation, deallocation, memory compaction, and fragmentation tracking.

🚀 Features
Implements First Fit, Best Fit, and Worst Fit memory allocation strategies.
Supports process deallocation and memory compaction.
Tracks and displays external fragmentation and free partitions.
Interactive command-line interface for live simulation.
📌 How It Works
User inputs:
Total memory size.
Number of processes and their sizes.
Desired allocation strategy.
The program allocates memory using the selected strategy.
Supports actions during runtime:
Deallocate a process.
Compact memory to reduce fragmentation.
Allocate new processes dynamically.
🛠️ Technologies Used
Java (Core)
Data Structures: ArrayList, HashMap, LinkedHashMap
Concepts: Dynamic Memory Allocation, Fragmentation, Partition Management
📄 Sample Input & Output (First Fit Strategy)
Enter total memory size: 550 Enter number of processes: 4 Enter process name: A Enter size for process A: 200 Enter process name: B Enter size for process B: 100 Enter process name: C Enter size for process C: 50 Enter process name: D Enter size for process D: 100 Enter allocation strategy (First Fit / Best Fit / Worst Fit): first fit

--- FIRST FIT Allocation ---

Process A allocated to partition 1 Process B allocated to partition 2 Process C allocated to partition 3 Process D allocated to partition 4

Partition Status: Partition 1: Size=200, Free=false, Process=A Partition 2: Size=100, Free=false, Process=B Partition 3: Size=50, Free=false, Process=C Partition 4: Size=100, Free=false, Process=D Partition 5: Size=100, Free=true

Free Partitions: Free Partition 5: Size=100

External Fragmentation: Total Free Memory: 100

Choose action: (d)eallocate, (c)ompact, (a)llocate new process, (e)xit: d Enter process name to deallocate: A Deallocated process A

Partition Status: Partition 1: Size=200, Free=true ...

Choose action: (a)llocate new process Enter new process name: G Enter size for process G: 100 Process G allocated to partition 5 ...

Choose action: (e)xit Exiting

yaml Copy Edit

🧪 How to Run
# Step 1: Clone the repository
git clone https://github.com/avgreddy/Dynamic-Memory-Allocation-Simulator.git
cd Dynamic-Memory-Allocation-Simulator

# Step 2: Compile the Java program
javac Main.java

# Step 3: Run the simulator
java Main
