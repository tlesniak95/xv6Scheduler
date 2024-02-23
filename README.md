# xv6Scheduler
Implemented a MLFQ - type scheduler along with a NICE value for each process

Features
Default Priority and Niceness: Ensures that new processes are initialized with default priority levels and niceness values.
Dynamic Priority Adjustment: Implements dynamic priority adjustments based on process behavior and system load.
Niceness Handling: Allows processes to adjust their priority through niceness, influencing their scheduling favorability.
Scheduler State Checks: Incorporates checks for scheduler states to handle invalid or null pointers, ensuring robust error handling.
Round-Robin Scheduling: Validates that processes with the same priority level are scheduled in a round-robin fashion for fairness.
Priority After Sleeping: Enhances priority handling to boost the priority of processes after waking from sleep, improving responsiveness.
Scheduling Policy: Ensures that runnable processes are scheduled effectively, respecting priority levels while maintaining system efficiency.
