# bf-solutions
Just messing around with brainfuck programming language.

# Brainfuck Programs

Welcome to the **Brainfuck Programs** repository! This repository is dedicated to code written in the Brainfuck programming language, including examples like "Hello World" and simple programs such as pattern printing and more.

## About Brainfuck

Brainfuck is an esoteric programming language created in 1993 by Urban Müller. It is known for its extreme minimalism, using only eight commands. Despite its simplicity, Brainfuck is Turing complete and capable of implementing any algorithm that can be executed on a Turing machine.

### Brainfuck Commands

- `>` : Increment the data pointer (move right).
- `<` : Decrement the data pointer (move left).
- `+` : Increment the byte at the data pointer.
- `-` : Decrement the byte at the data pointer.
- `.` : Output the byte at the data pointer.
- `,` : Input a byte and store it at the data pointer.
- `[` : Jump forward to the command after `]` if the byte at the data pointer is 0.
- `]` : Jump back to the command after `[` if the byte at the data pointer is not 0.

## Programs

### 1. Hello World
The classic "Hello World" program written in Brainfuck.

```brainfuck
+[-->-[>>+>-----<<]<--]<---.>>>+.>++.+++++++..+++.[--->+<]>---.<<.+++.------.--------.>>+.>++.
