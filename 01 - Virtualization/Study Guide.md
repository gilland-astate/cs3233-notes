## Know These Sections for Knowledge
### Chapter 2
- Virtualization for CPU and Memory
- The role of the OS in these items
- Know what/how Concurrency Works and Functions
- Importance of Concurrency in multiprogramming
- Persistence of State and Data
- Key Goals of OS (4 major, 3 minor)
- Basic History of Operating Systems
### Chapter 4
- The Basic Abstraction concept behind a process
- What a process looks like from a component perspective
- Process API
- How process creation works
- Basic Process States + Transitions 
- Data Structures in the OS itself
### Chapter 5
- Basic Concurrency, fork(), wait(), exec()
- Process Control
### Chapter 6
- Basic DE Technique
- Restricted Operations
	- User/Kernel Mode
	- Calls and Traps
- Switching Processes
	- Cooperative vs Non-Cooperative
	- Context Switching
	- Timer Interrupt
	- Hardware/Software Responsibilities
- Dealing with Concurrency while multiprogramming
### Chapter 7
- Scheduling Algorithms and Metrics
- Best Algorithm for Particular Choices
- Key CPU Virtualization Terms (Mechanisms)
### Chapter 8
- Basic MLFQ Rules/Benefits
- Problems with basic MLFQ and how we can work to solve them
- Configuration Options for MLFQ
- Nice in Linux
### Chapter 13
- Multiprogramming and Time Sharing
- Address Space
- Virtual Addressing/Memory Virtualization
- Goals of VM
### Chapter 15
- Basics of Memory Virtualization
- Hardware-based Memory Relocation
- Hardware Support for Virtual Memory
- Operating System Issues of implementing VM
### Chapter 16
- Basic Implementation details for Segmentation
- Logical Segmentation
- Translation Process/Seg Fault
- Implicit vs Explicit Segment selection
- Sharing VM with segmentation
- Fine-grain vs Coarse grain segmentation
- External Fragmentation and how to reduce it
### Chapter 18
- Segmentation vs Paging
- Advantages of Paging
- Internal Fragmentation
- Address Translation using Paging
- Cons to using Paging
- Contents of a PT and PTE
- How we can speed up Paging
### Chapter 19
- What TLBs are
- Basic TLB Algorithm
- How TLB Misses are Handled
- Software vs Hardware TLB
- Issues with TLB and Context Switch
### Chapter 20
- How we can combine Segmentation and Paging
- Multi-Level Page Tables
- How multiple page tables work and how we can increase past 2
- Swapping PT to disk
### Chapter 21
- Swapping 
- Page Faults
- Page Replacement Policy
- Page Fault Control Flow
- High/Low Watermarks
### Chapter 22
- AMAT Formula
- MIN
- Hit Rate Calculation
- FIFO
- LRU
## Know Application of these Topics
- Basic Concurrency, fork(), wait(), exec()
- Scheduling Algorithms and Metrics
- Basic Address Translation with Logical to Physical Address 
- Free-List Management Algorithms
- Address Translation using Segmentation
- Address Translation using Paging
- Checking Logical Address Legality by comparing current PT
- AMAT Formula
- Hit Rate Calculation

## Please note this is not an exhaustive list and study should not rely on this alone. There are also python simulations available below:
https://github.com/remzi-arpacidusseau/ostep-homework/
