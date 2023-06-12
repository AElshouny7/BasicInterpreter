# Description

The project focused on constructing a correct architecture that emulates a real operating system. Developed an interpreter that reads program files in text format and executes their code. The interpreter was responsible for processing instructions and managing processes within the simulated operating system.

Key components of the project included:

* System Calls: I implemented essential system calls that enable processes to request services from the operating system. The system calls included functionalities such as reading and writing data from/to files, printing data on the screen, and taking text input from the user.
  
* Memory Management: I designed a memory management system that allocated space for processes in the main memory. The memory had a fixed size of 40 memory words and was responsible for storing program instructions, variables, and Process Control Blocks (PCBs). To manage cases where the memory was insufficient, I developed a mechanism to unload processes to disk and swap them back into memory when necessary. Memory Management: I designed a memory management system that allocated space for processes in the main memory. The memory had a fixed size of 40 memory words and was responsible for storing program instructions, variables, and Process Control Blocks (PCBs). To manage cases where the memory was insufficient, I developed a mechanism to unload processes to disk and swap them back into memory when necessary.

* Mutexes: I implemented mutexes to ensure mutual exclusion over critical resources. Three mutexes were utilized for accessing files, managing user input, and managing screen output. The mutexes relied on semWait and semSignal operations to control access to the shared resources.

* Scheduler: I incorporated a Round Robin scheduling algorithm to manage the execution of processes. Each process was assigned a fixed time slice, and the scheduler ensured fair execution by periodically switching between processes in the Ready Queue.

Throughout the project, I paid attention to both correct implementation and the overall architecture of the simulated operating system. Developed a code parser/interpreter, implemented system calls, designed mutexes, devised a scheduler, and managed memory effectively.

This project allowed me to deepen my understanding of operating system concepts, strengthen my programming skills, and enhance my ability to design and build complex systems. It served as a valuable learning experience in simulating an operating system environment and its key components.
