# Shared Memory

Inter Process Communication
A process can be of two type:

1. Independent process.
2. Co-operating process.
An independent process is not affected by the execution of other processes while a co-operating process can be affected by other executing processes. Though one can think that those processes, which are running independently, will execute very efficiently but in practical, there are many situations when co-operative nature can be utilised for increasing computational speed, convenience and modularity. Inter process communication (IPC) is a mechanism which allows processes to communicate each other and synchronize their actions. The communication between these processes can be seen as a method of co-operation between them. Processes can communicate with each other using these two ways:
1. Shared Memory
2. Message passing


Shared memory is a segment of memory that is shared between processes.  It is an efficient means of passing data between programs. One program will create a memory portion which other processes (if permitted) can access. 

References: www.geeksforgeeks.com for theory
