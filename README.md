# Simple UNIX Command Interpreter (Shell)

This project is a basic UNIX command interpreter, commonly known as a shell. It enables users to communicate with the operating system by entering commands and executing them.

## How it Works

The shell acts as a mediator between the user and the operating system. When a user inputs a command, the shell interprets it, performs the necessary actions, and communicates with the operating system to execute the command. 

## Key Concepts

Here are some essential concepts to understand about this shell:

* Process ID (PID) and Parent Process ID (PPID): Every process running on the system is assigned a unique PID. PPID refers to the PID of the process that created the current process.

* Environment Manipulation: The shell allows manipulation of the environment of the current process, including variables and settings.

* Function vs. System Call: Functions are blocks of code that perform specific tasks within a program, while system calls are requests made by a program to the operating system for services such as file operations or process management. 

* Creating Processes: The shell can create new processes using system calls provided by the operating system, allowing for concurrent execution of multiple programs. 

* Main Prototypes: The `main` function, which serves as the entry point for a program, can hace three prototypes:
	
	* `int main()`
	* `int main(int argc, char *argv[])`
	* `int main(int argc, char *argv[], char *envp[])`

* Using PATH to Find Programs: The shell uses PATH environment variable to locate executable programs specified by the user. 

* Executing Programs with `execve`: The `execve` system call is used to execute another program, replacing the current process with the specified program.

* End-of-File(EOF): EOF is a special character that marks the end of a file when reading data. 

## Getting Started

To run the shell, follow these steps:

1. Clone the repository to your local machine.
2. Compile the shell source code using your preferred compiler.
3. Execute the compiled binary to start the shell. 

## Contributions

Contributions to this project are welcome! If you have ideas for improvements or new features, feel free to submit a pull request. 

## Acknowledgments

This project was inspired by ALX Simple shell project to create a simple UNIX command interpreter and the desire to understand the inner workings of shells and operating systems.
