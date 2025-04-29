This journal documents my learning progression in the “Tech for Social Good” course.

- Observing Technology in the Environment
We walked through campus observing embedded technologies like CCTV cameras, biometric scanners, access-controlled gates, and digital display boards. We discussed their hardware components (sensors, processors, output displays) and software systems that power them.
Conceptual Link to Unit 1:
Types of computers: Embedded systems and personal computing devices
Real-time applications of software in surveillance and automation
Introduction to human-computer interaction through UI elements
We also used Google Sheets and Gmail scripting to automate email sending—an example of software-based automation aiding communication.


- Instruction Execution in CPU & Bus Architecture
This class deepened our understanding of how a CPU executes instructions using load-store architecture. We were introduced to:
	Accumulator: temporary storage in ALU
	Control signals and data buses
	Registers: IR (Instruction Register), PC (Program Counter)
We examined how instructions like LOAD and ADD are translated to binary and move through the CPU for execution.
Conceptual Link to Unit 1:
	Fetch–decode–execute cycle
	Role of buses: Address Bus (locates data), Data Bus (transfers data)
	CPU instruction handling using transistor logic (AND/OR gates)

- Binary Number Quiz
We were quizzed on binary arithmetic, conversion, and its role in instruction execution. The quiz tested speed, accuracy, and understanding—cementing the binary-to-hardware relationship.

- Installing and Running Linux (WSL)
We installed Windows Subsystem for Linux (WSL), allowing a Linux environment to run within Windows. This introduced us to:
	Linux kernel and shell interface
	Installing packages and launching terminals
	Using bash as the default command interpreter
Conceptual Link to Unit 2:
	Structure of Linux: Kernel → Shell → Applications
	Introduction to CLI (Command Line Interface)
	Importance of open-source ecosystems and software freedom


- PowerShell for File Management
We explored Windows PowerShell to:
	Create folders (mkdir)
	Navigate directories (cd)
	Move, delete, and organize files
We also practiced separating files (e.g., MP3s, PDFs) using scripts—early exposure to automation via scripting.

- Basic Linux Commands & History
We dove deeper into Linux using the shell:
	ls, rm, ps-aux, mkdir, cd
	User roles: root, standard user
	Multi-user and multitasking support in Linux
We also covered:
	History of Unix → GNU/Linux
	Contributions from Linus Torvalds, Richard Stallman
Conceptual Link to Unit 2:
	Linux architecture and core features
	File system hierarchy
	Understanding permissions (chmod)

- Team Presentations
We gave short team presentations on: 
Computer Organization" (referencing the book by Hamcher)
The presentation serves as an educational introduction to how computers are structured, how they process instructions, and what influences their performance—targeting students or learners in computer science or engineering. It combines theoretical concepts (e.g., CPU equations) with practical examples (e.g., memory hierarchy) and historical context.


- Advanced Shell Scripting
We learned:
	How to use pico editor to create .txt files
	Automating renaming with for loops:

bash
CopyEdit
for i in * ; do mv "$i" "$i.txt" ; done
	File permissions: chmod +x filename
	Process management: ps-aux, kill
Conceptual Link to Unit 2:
	Importance of shell scripting for automation
	File execution, permissions, and ownership
	Running and managing background processes

- Linux Bootable USB
We created bootable Linux installations using Ventoy and Rufus tools, learning how to:
	Format drives to FAT32
	Use ISO images
	Boot Linux outside of Windows
Conceptual Link to Unit 1 and 2:
	System boot process and BIOS/UEFI role
	Hardware-software interface during OS loading
	Running OS from external media

- Shell Command Quiz
We were tested on:
	Creating/deleting directories
	Permissions and file access
	Using grep, find, chmod, nano/pico
The quiz reinforced memorization and usage of essential Linux commands.

- Mass File Operations
Using for loops and mv commands, we learned to:
	Rename multiple files at once
	Add .txt extensions to all files
	Execute scripts in a directory for automation
Also practiced:

bash
CopyEdit
chmod +x script.sh
Relevance:
	Demonstrates power of scripting in Linux
	Automates redundant manual tasks

- Email Tools and Hardware Interfaces
We discussed:
	Online tools like Mailchimp for mass communication
	I/O interfaces in hardware: USB, HDMI, serial/parallel ports
	Data transfer modes: synchronous vs asynchronous
Conceptual Link to Unit 1:
	I/O Unit and peripheral communication
	Software protocols for email, cloud tools

- IP Addressing & Networking
Learned about:
	IPv4 and IPv6 addressing
	DNS, ARP, DHCP
	How data is split into packets (TCP/IP model)
	Tools like ping, traceroute
Conceptual Link to Unit 1:
	Data packaging and transmission
	Protocols ensuring reliable communication
	Real-world example: pinging servers to check latency

- Git with WSL
Worked on Git version control using Linux:
	Initializing repositories with git init
	Committing notes created in pico
	Pushing files to GitHub
This bridged Linux terminal knowledge with software development tools.

- Neural Networks (Guest Lecture)
Expanded on ANN with:
	Forward pass and activation functions (ReLU, Sigmoid)
	Loss functions and optimization (Gradient Descent)
	Need for non-linearity to solve XOR
	Splitting data: training, validation, testing
Conceptual Connection:
	Understanding deeper layers in neural networks
	Limitations of perceptron without hidden layers
	Foundational for modern AI/ML systems
