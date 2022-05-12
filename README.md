Build a virtualized 16-bit computer from first principles, capable of running simple games like Tetris.
https://www.nand2tetris.org/
This project is an excellent stepping off point for learning abstraction (what a module does) and implementation (how a module does it) in computer science.
The project has two sections: first building a (simulated) hardware platform capable of running programs written in the Hack machine language, and then second building a software architecture that runs a virtual machine, a compiler to interpret the high level language Jack, and a basic operating system.

The project starts from building logic gates for bit manipulation, then those simple gates are used to build more complex circuits like adders, ALU, and memory. We then build an assembler to assemble hardware executable binary instructions from assembly code. 
The second half of the project starts with building a basic virtual machine translator to serve as the backend for a compiler that translates VM commands into machine language. Then the front end of the compiler is built to parse Jack--a simple object oriented programming language similar to Java--into VM code. Lastly a subset of basic operating system services is built in Jack - math operations, string and array types, memory, graphic output, character output, keyboard input, and some execution related system services.
