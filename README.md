**0x19. C - Stacks, Queues - LIFO, FIFO**
 
**The Monty language**
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.
Monty byte code files
Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument:

**The monty program**
•	Usage: monty file
o	where file is the path to the file containing Monty byte code
•	If the user does not give any file or more than one argument to your program, print the error message USAGE: monty file, followed by a new line, and exit with the status EXIT_FAILURE
•	If, for any reason, it’s not possible to open the file, print the error message Error: Can't open file <file>, followed by a new line, and exit with the status EXIT_FAILURE
o	where <file> is the name of the file
•	If the file contains an invalid instruction, print the error message L<line_number>: unknown instruction <opcode>, followed by a new line, and exit with the status EXIT_FAILURE
o	where is the line number where the instruction appears.
o	Line numbers always start at 1
•	The monty program runs the bytecodes line by line and stop if either:
o	it executed properly every line of the file
o	it finds an error in the file
o	an error occured
•	If you can’t malloc anymore, print the error message Error: malloc failed, followed by a new line, and exit with status EXIT_FAILURE.
•	You have to use malloc and free and are not allowed to use any other function from man malloc (realloc, calloc, …)

**Functioning**
1. push and Pall opcodes
2. pint opcode
3. pop opcode
4. swap opcode
5. add opcode
6. nop opcode
7. sub
8. div
9. mul 
10. mod
11. pchar
12. pstr
13. rotl
14. rotr
15. stacks and queue





