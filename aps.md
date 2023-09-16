# 1 self introduction

## 1.1 basic information

hello, dear

My name is Zhang Ming, a software engineer, currently working in a start-up company in Chengdu, China. 

I graduated from the Dalian University of Technology in june, 2022.

I majored in software engineering during my university years and accumulated a wealth of project experience during this period.

My hobby, is playing badminton.



## 1.2 university and motivation  

why choose Germany?

1. German universities rank among the best in the world, offering high-quality education.
2. Germany is a leader in the field of research, offering abundant research opportunities and resources.
3. Germany has a rich culture and history, making it an ideal place to study European history and culture.

why choose bonn

1. The University of Bonn is one of eleven Universities of Excellence in Germany. Over the past few decades, we have produced more Nobel and Fields laureates
2. Studying at the University of Bonn means learning from internationally leading academics working at the cutting edge of their subject.
3. Bonn is a modern, happy, and cosmopolitan city with an exceptionally high quality of life.

# 2 Public course

## 2.1 linear algebra and analytic geometry

### 2.1.1 introduction



### 2.1.2 basic knowledge 

## 2.2 Mathematical Analysis for Engineering

## 2.3 Discrete Mathematics

## 2.4 Probability and statistics



# 3 Professional course

## 3.1 ***Fundamental** of Computer

### 3.1.1 introduction

The university computer basics course is a course covering all aspects of computer science, including the foundation of computer systems, the representation of information and the basic working principles of computers**, the foundation of operating systems**, the foundation of **computer networks**, the foundation of **programmin**g, the foundation of **databases**.

### 3.1.2  points

#### 3.1.2.1 The structure of a computer system

hardware+software

hardware:arithmetic unit, controller, memory, input device, and output device

software:program+data 

program:system software+application system



**The structure of a von Neumann type computer**

programs and data in external memory ,are first loaded from the external memory into the memory

(1) Represent programs and data in binary form.

(2) Computer hardware is composed of five major parts: arithmetic unit, controller, memory, input device and output device.

(3) Programs and data are stored in memory in binary form.

(4) The controller works according to the instructions (program) stored in the memory.

**Harvard architecture** is a memory structure that separates program instruction storage and data storage

**The difference** between the two is whether the program space and data space are integrated. Von Neumann structure data space and address space are not separated, Harvard structure data space and address space are separate.

#### 3.1.2.2 the representation of information

#### 3.1.2.3 operating system

#### 3.1.2.4 data and structure

## 3.2 ***Program** Basis

### 3.2.1 introduction

Basic ideas and methods of programming, including programming ideas, basic structures, algorithms, and basic data structures



### 3.2.2  points

#### 3.2.2.1 control structure

sequential structure
Select structure
Loop structure

#### 3.2.2.2 basic grammar of c language

#### 3.2.2.3 data structure

#### 3.2.2.4 algorithm

#### 3.2.2.5 oop

**encapsulation**
Use abstract data types to encapsulate data and data-based operations to form anindependent entity. The data is protected within the abstract data type.
**inherit**
Inheritance is a technology that uses the definition of an existing class as a basis to create a new class. The definition of a new class can add new data or new functions, or use the functions of the parent class, but it cannot selectively inherit the parent class.
**Polymorphism**
Polymorphism means that after the properties and methods defined in the parent class are inherited by the subclass, they can have different data types or show different behaviors. This makes the same property or method have different properties in the parent class and its subclasses. meaning

## 3.3 ***Engineering** numerical method

Numerical Methods in Engineering is a course that studies how to use numerical methods to solve engineering problems



**Numerical Integration**: Learn how to perform integration using numerical methods.

Trapezoidal integral, Simpson integral, adaptive integral, Romberg integral and Gaussian integral

**Numerical Optimization Methods**: Learn how to use numerical methods for optimization.
**Numerical Computation of Differential Equations**: Learn how to solve differential equations using numerical methods.

Numerical solution: use several discrete points to calculate approximate values instead of exact values
Euler's method: Use matrix area instead of surface trapezoidal area
Improved Euler method: replace the trapezoidal area of the curved surface with the trapezoidal area
Runge-Kutta method:
Adams method: It is a linear multi-step method that uses multiple calculated values to perform calculations.
Lagrangian interpolation: constructor polynomial to approximate instead
The Adams method is approximately replaced by the functional polynomial of Lagrangian interpolation

## 3.4 !!!@Computer Organization and structure

### 3.4.1 introduction

The hardware composition and working principles of computers, including knowledge of the composition of computer systems, data representation and processing, instruction systems, storage systems, input and output systems, and computer performance.

### 3.4.2 points

#### 3.4.2.1 **Representation and processing of data**: Learn how to describe data in programs

**IEEE floating point representation IEEE 754**
$V=(-1)^s * M*2^E$

example:

S E M
0 1-8 9-31
S is the sign bit, 1 is negative and 0 is positive

e is the value of the binary code in the E stage, and f is the binary decimal value in the M stage.

E is the exponent code. All 0s and all 1s are special values. Others are normal. The range is 0000 0001-1111 1110:

E is all 0, which is a non-standard number. E takes -6 (1-bias), and M takes f.
E all 1's is infinity
E is all 1, M is not all 0, it is NaN
Normalized number E=e-bias, M is 1+f
bias is 127()k is the number of digits in E

#### 3.4.2.2 system bus

**Data Bus**
Function: transmit data
It's two-way
The line width of the data bus = machine word length = main register length, which is generally equal to the storage word length.
**address bus**
Role: Determine the source or destination of data
It's two-way
The line width of the address bus determines the maximum capacity of the memory, that is, the maximum number of storage units
**control bus**
Function: Transmit control signals
is one-way

PCI/USB

**structure:**

Single bus structure
Dual bus structure
Three bus structure
In the three-bus structure, a new DMA (direct memory access) bus is added

**Synchronous communication principle**

 Synchronous communication is a communication method that continuously transmits data serially. Only one frame of information is transmitted at a time. When using synchronous communication, many characters are composed into an information group, so that the characters can be transmitted one after another. However, a synchronization character is added at the beginning of each group of information (usually called a frame). When there is no information to be transmitted, Blank characters should be filled in because synchronous transmission does not allow gaps.

**Asynchronous communication principles**
When sending characters in asynchronous communication, the time interval between the characters sent can be arbitrary. Of course, the receiving end must always be ready to receive. The sending end can start sending characters at any time, so it must add flags at the beginning and end of each character, that is, add a start bit and a stop bit, so that the receiving end can correctly receive each character. The advantage of asynchronous communication is that the communication equipment is simple and cheap, but the transmission efficiency is low (because the start bit and stop bit overhead account for a large proportion).

#### 3.4.2.3 memory

A memory device in a computer system used to store programs and data
Main memory/cache/auxiliary memory
Main memory: ram/rom
ram:static/dynamic
rom:mrom/prom/eprom/eeprom

structure:

![image-20230916105818586](./assets/image-20230916105818586.png)

**register**:

It is the internal component unit of the CPU and is the fastest place for fetching instructions and data during CPU operations. It can be used to temporarily store instructions, data and addresses. In the control unit of the CPU, the registers included are the instruction register (IR) and the program counter (PC). The arithmetic logic component of the CPU contains registers such as the accumulator (ACC)

**cache:**

Temporal locality and spatial locality.
direct mapping
Direct mapping uses a "modulo" method for one-to-one mapping.

Group association:
In direct mapping, each data block in main memory has a certain cache line for mapping, which is flawed.

Fully connected
Fully associative is an extreme form of set associativity, that is, the cache has only one cache set. Each data block can be stored in any cache line. The figure below shows the corresponding relationship.

#### 3.4.2.4 instruction 

implicit addressing
The operands are implicitly given by the accumulator
Address immediately
The corresponding operands are given directly in the instruction.
register direct addressing
The register number R is given in the command, and the operand is stored in R.
register indirect addressing
The register number R is given in the instruction, and the effective address of the operand is stored in R.
Direct addressing
The effective address of the operand given in the instruction
Indirect addressing
The instruction gives the memory unit address where the effective address E is stored.
relative addressing
The offset A relative to PC is given in the instruction
base addressing
The offset relative to the base register R is given in the instruction.
indexed addressing
The offset relative to the index register R is given in the instruction.

## 3.5 ***Computer** Organization and Structure Experiment



## 3.6 *Data structure and algorithm

The content of data structure research is how to organize data according to a certain logical structure. Generally, learning algorithms start from the data structure, first determine the data structure based on the actual problem, and then design the algorithm based on the data structure.

### 3.6.1 linear table

linked list

logic consequent but physical discrete

### 3.6.2 queue and stack

queue first in first out

stack first in and last out

stack.push add a element to the top of stack

stack
A linear table that allows insertion or deletion at one end only.
Top of the stack: The end of the linear list that allows insertion and deletion.
Bottom: Fixed, the other end that does not allow insertion and deletion.
A stack that uses sequential storage is called a sequential stack. It uses a set of storage units with consecutive addresses to store data elements from the bottom of the stack to the top of the stack. It also has a pointer (top) attached to indicate the current top position of the stack.
A stack that uses chained storage is called a chain stack. The advantage of a chain stack is that it facilitates multiple stacks to share storage space and improves its efficiency, and there is no stack overflow. It is usually implemented using a singly linked list, and all operations are performed at the header of the singly linked list.



A queue is a linear list that only allows insertion operations at one end and deletion operations at the other end.
The queue is a first in first out (First In First Out) linear table, referred to as FIFO.

The end that allows insertion is called the rear, and the end that allows deletion is called the front.

Inserting a new data element into the queue is called enqueuing, and the newly enqueued element becomes the tail element of the queue.

Removing the head element from the queue is called dequeuing, and its subsequent elements become the new head element.

chain&sequential

### 3.6.3 tree

The root node of the tree has no predecessor, and all nodes except the root node have one and only one predecessor.
All nodes in the tree can have zero or more successors.

Binary tree is another tree structure, which is characterized by that each node has at most two subtrees

full binary tree 

complete binary tree

preorder inorder postorder



Level traversal



Binary sorting tree
**Self-Balancing Binary Search Tree**

Huffman tree

### 3.6.4 sorting algorithm

Bubble Sort

selection sort
insertion sort
Hill sort
merge sort
Quick sort
Heap sort
counting sort
bucket sort
Radix sort

## 3.7 *operating system

A course that studies how to effectively manage and schedule computer system resources

### 3.7.1 process

A process is a program running in the operating system. The process is loaded into memory, and the CPU executes its instructions.
Concurrency: When a CPU performs multiple tasks, it switches execution back and forth between each task. Each task executes for a short time slice, making it appear as if multiple tasks are executed at the same time.
Parallelism: Multiple CPUs execute multiple tasks at the same time, each CPU executes one task, and the tasks are executed simultaneously.
Creation state, ready state, running state, blocking state and end state
Ready -> Running:  is scheduled by the scheduler

Running -> Ready: no longer being executed

Running -> Blocking:  requests to call certain system services

Blocking -> Ready: When the waiting is over,

Run -> Terminate: After the process execution is completed, it will be terminated by the operating system.

A **thread** is a basic unit that is smaller than a process and runs independently. It is also an execution flow in a process and the basic unit of CPU scheduling.

**Process communication metho**d
Pipes, message queues, shared memory, semaphores, signals, sockets

### 3.7.2 cpu scheduling

First come, first served (non-preemptive)
First Come First Serverd (FCFS). If the queue is advanced, it will be scheduled first.
Time slice rotation (preemptive)
Each process will be assigned a time slice, and the process will run during this time period. If the time expires and the process has not finished running, the CPU will be allocated to other processes through preemptive scheduling, and the process will return to the ready queue.
Shortest job first
Shortest Job First (SJF), that is, processes are queued according to the length of the job, and those with the shortest job time are executed first.
priority scheduling

### 3.7.3 deadlock

In multiple concurrent processes, if each process holds a certain resource and is waiting for other processes to release other resources, it cannot move forward until this state is changed.
There are 4 conditions for deadlock (if one condition is not met, deadlock will not occur):
**Mutual exclusion**: a resource can only be used by one process at a time
**Request and hold**: When a process is blocked due to requesting resources, it holds on to the obtained resources.
**Non-preemption**: The resources obtained by the process cannot be forcibly preempted before they are completely used.
**Circular waiting:** Several processes form a head-to-tail circular waiting relationship for resources.

**Deadlock prevention**
Deadlock prevention is to prevent deadlock before the program runs, that is, to destroy the four necessary conditions for deadlock to occur. Deadlock avoidance can be thought of as dynamically avoiding deadlocks during program execution, while deadlock prevention can be said to be a static approach that eliminates the possibility of deadlocks.

1. Destroy mutual exclusion conditions: Try to prevent resources from being exclusively occupied by a certain process.


2. Destroy possession and waiting conditions: prohibit processes that already hold resources from waiting for other resources

3. Destroy the non-preemption condition: just allow resource preemption.

4. Break the loop waiting: One method is to number the resources. The process can request the resources at any time, but all requests must be made in the order of the resource numbers (ascending order).

1. Resource trajectory map

If you know what resources the process requires at each stage, you can label the process in the diagram. The overlapping area of two processes is an area that can cause deadlock. In order to avoid deadlock, a process should be blocked at the right time so that the operation avoids this area.

2. Banker’s Algorithm

The main idea of the Banker's algorithm is to prevent the system from entering an unsafe state. During each resource allocation, it first checks whether the system has enough resources to meet the requirements. If so, it allocates it first and performs a security check on the new state after allocation. If the new state is safe, the above resources are officially allocated, otherwise the allocation of the above resources is refused. In this way, it ensures that the system is always in a safe state, thereby avoiding the occurrence of deadlock.

### 3.7.4 vm

three problem:Insufficient memory, memory fragmentation, and mutual modification of memory between programs

**Insufficient memor**y: When applying for memory from the system but there is insufficient memory, the system will replace the temporarily unused memory to the hard disk according to the replacement algorithm, update the mapping relationship to the hard disk, and then update the newly applied memory mapping relationship, allowing us to generate infinite The illusion of memory.
**Memory fragmentatio**n: The program can find suitable physical memory at will through its own mapping table, and does not necessarily need to be allocated continuously.
  **The same address between programs**: Even if the addresses of the programs are the same, each program maps to different physical memory through its own mapping table without interfering with each other.



A **page table** is a data structure used in the virtual memory system of a computer operating system that stores the mapping between virtual addresses and physical addresses.
**How programs access memory: address translation**
The program specifies a logical address to load
The computer converts logical addresses into physical addresses through mapping
If the physical address is not in the memory, the operating system will load it from the hard disk into the memory and update the mapping relationship (it originally pointed to the disk, but now points to the memory)
The computer reads the memory content through the physical address and returns it to the program



**Page replacement algorithm**

1. Optimal replacement algorithm OPT Each time the page that has not been visited for the longest time is selected, it will be eliminated to ensure the lowest page missing rate. Since it is impossible to predict the future, it is virtually impossible to achieve. 
2.  First-in-first-out replacement algorithm FIFO Each time the page that enters the memory earliest is eliminated. Arrange the pages into a queue in order, and eliminate the page at the head of the queue each time.
3. the most recently used algorithm LRU Each time the most recent and least used pages are eliminated. The performance is good, but the overhead is high. Requires hardware support.

## 3.8 *Computer network

| five        | seven        | protocol              | function                                                     |
| ----------- | ------------ | --------------------- | ------------------------------------------------------------ |
| application | application  | ftp/http/dns/sptp/pop | Provides an interface for an operating system or network application to access network services. |
|             | presentation |                       | layer data or information to ensure that one host application layer information can be understood by another host application |
|             | session      |                       | The session layer manages session processes between hosts, that is, it is responsible for establishing, managing, and terminating sessions between processes. |
| transport   | transport    | tcp/udp               | The transport layer is responsible for segmenting upper layer data and providing end-to-end, reliable or unreliable transmission, as well as end-to-end error control and flow control issues; |
| network     | **Network**  | ip/icmp/arp           | Achieve transparent data transmission between two end systems. Specific functions include addressing and routing, connection establishment, maintenance and termination. |
| datalink    | data link    |                       | Frame is the transmission unit of the data link layer<br/>Provide transparent and reliable data transmission services to the network layer<br/>Data link management, encapsulation into frames, transparent transmission, error control.<br/>Ethernet protocol<br/>Bridges and switches |
| physical    | physical     |                       | Repeaters and hubs。。。Activating, maintaining, and deactivating mechanical, electrical, functional, and process characteristics between communication endpoints. This layer provides a reliable physical medium for transmitting data to upper layer protocols. |

POP3 TCP 110
IMAP TCP 143
SMTP TCP 25
Telnet TCP 23
HTTP TCP 80
FTP(控制) TCP 21
FTP(数据) TCP 20
HTTPS TCP 443
DHCP UDP 67
DNS UDP 53
DNS TCP 53

### 3.8.1 HTTP

Hyper Text Transfer Protocol

HTTP is a protocol based on TCP/IP communication protocol to transmit data. The data types transmitted are HTML files, image files, query results, etc.
**request message**
Request line: including request method, URL, protocol/version
Request Header
request body
**Response message** composition
status line
response header
Response body

GET: Requests the specified page information and returns the entity body.
POST: Submit data to the specified resource to process the request (such as submitting a form or uploading a file). The data is included in the request body. POST requests may result in the creation of new resources and/or modification of existing resources.
HEAD: Similar to a get request, except that there is no specific content in the returned response, used to obtain headers
PUT: Data transferred from the client to the server replaces the content of the specified document.
DELETE: Request the server to delete the specified page.

200 OK - Client request successful
301 - The resource (web page, etc.) has been permanently moved to another URL
302 - Temporary jump
400 Bad Request - The client request has a syntax error and cannot be understood by the server.
401 Unauthorized - The request is not authorized. This status code must be used with the WWW-Authenticate header field.
404 - The requested resource does not exist. You may have entered the wrong URL.
500 - An unexpected error occurred within the server
503 Server Unavailable - The server is currently unable to handle the client's request and may return to normal after a period of time.

### 3.8.2 DNS



## 3.9 *Object-oriented Method and C++ program Design

## 3.10 *Analog and Digital Circuit

## 3.11 ***Database** System

## 3.12 *Compiler technology

## 3.13 *Software Engineering

## 3.14 *Network Inoformation security

## 3.15 network comprehensive experiment

## 3.16 IT ethics and professional accomplishment

## 3.17 *software project management

## 3.18 *system analysis and design

## 3.19 @**course** design of professional direction

## 3.20 practice training

## 3.21 @Single chip of  Microcomputer pronciple and application design

## 3.22 @FPGA design and application

## 3.23 @Java advanced programming and application

## 3.24 @J2EE advanced  programming

## 3.25 @embedded software design

## 3.26 @principle and design of embedded system

## 3.27 @Embedded hardware design

## 3.28 @intelligent embedded operating system technology

## 3.29 @python

## 3.30 @formalized design and test of embedded software

# 3 graduation design



# 4 important course

## 4.1 compiler technology

A compiler is a computer program that translates one language into another.
A compiler takes a written program as input and produces an equivalent program written in the target language.
Source program → {compiler} → target program

1. Scanner: The scanner performs lexical analysis and collects sequences of characters into units called tokens.
2. Syntax analyzer: Obtains source code in token form from the scanner and completes syntax analysis that defines the program structure. The result of syntax analysis is usually expressed as a parse tree or syntax tree.
3. Semantic Analysis of Programs: The semantics of a program determine the operation of the program. These features are called static semantics. The task of the semantic analysis program is to analyze these semantics. The additional information computed by the semantic analyzer is called attributes, and the output is an annotation tree.
4. Source code optimization program
5. Code generator: The code generator gets the intermediate code and generates the code for the target machine.
6. Target code optimizer: optimize target code

### 4.1.1 Lexical Analyzer

Read the source program as a character file and divide it into tokens

Lexical Analyzer
It is a process of identifying tokens and sending the tokens to the syntax analyzer. Each word or symbol is converted into a corresponding internal identification code (token) and sent to the syntax analyzer or parser.

Lexical analyzers are implemented through finite automata.
The nodes of the automaton represent the current state, and the edges represent the accepted inputs.
The double arrow represents the initial state, and the double line circle represents the terminal state.

### 4.1.2 syntax analyzer

Grammatical analysis: lexical token (token) flow->grammatical phrase (parse tree)

Eliminate left recursion: eliminate left recursion
extract left common factorsextract left common factors
LL analysis method:
Find the First set, which is the set of first terminal symbols in the sentence fragment.
Find the follow set of symbols. In each sentence pattern of syntax G, the terminal symbol that can be followed by A is
Find the Select set, the optional set of productions
Construct the Predicting Analysis Table, that is, combine the left side of each production with the terminal symbol in the select set,
The predictive analysis system starts from the root of the tree, takes out a non-terminal symbol, puts it in the buffer, takes a terminal from the input buffer, searches it in the select set, and replaces the original non-terminal symbol with the output result name.
If the left side of the derivation string and the left side of the input buffer are both terminals, output and eliminate
Repeat the above steps until there is nothing left in the derivation buffer.

1. 消除左递归：eliminate left recursion
2. 提取左公因子extract left common factors

LL分析法:

- 求出First集，First集是句子片段中的首终结符集
- 求出后续符号集Follow set，句法G的各个句型中，A后面可以跟的终结符terminal symbol
- 求出Select集，产生式的可选集
- 构造预测分析表Predicting Analysis Table，也就是将每个产生式(production)的左侧与select set中的terminal symbol进行组合，
- predicting analysis system从树根开始，取出一个非终结符non-terminal symbol，放到buffer中，从input buffer中拿一个terminal, 在select set 里查找，输出结果名替换掉原来的非终结符
- 如果推导串左侧和输入缓冲区的左侧都是terminal，输出并消去
- 重复上述步骤知道推导buffer里没有剩余

### 4.1.3 Semantic Analyze语义分析

根据syntax parsing tree生成中间代码three-address code三地址码。Three-address code 以四元式quaternary的形似出现。

而我们通常在第三步真正使用的是Syntax-Directed Definitions，SDD语法制导翻译。在每个production上添加action，在每个symbol上附加attribution。

代码优化  Code Optimizing

## 4.2 software engineering

Apply systematic, standardized, and quantifiable methods to the development, operation, and maintenance of software, that is, apply engineering methods to software.

### 4.2.1 
