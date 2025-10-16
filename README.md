Compiler Construction Laboratory
Overview:
This repository showcases a collection of practical experiments and assignments completed for the Compiler Construction Laboratory course.
This lab aims to gain a comprehensive understanding of how compilers function — exploring each stage from lexical analysis to code generation by implementing them programmatically.

Objectives:
1. Develop a clear understanding of the structure and workflow of compilers.
2. Implement core components such as lexical analyzers, syntax analyzers, and semantic analyzers.
3. Learn how high-level source code is translated into intermediate or target machine code.
4. Gain practical experience using Lex/Flex and Yacc/Bison tools (or equivalent compiler tools).
5. Strengthen theoretical compiler concepts through hands-on coding and experimentation.

How to Execute:
Clone the Repository
git clone https://github.com/your-username/compiler-construction-lab.git
cd compiler-construction-lab

Running Lex & Yacc Programs
lex program.l
yacc -d program.y
gcc lex.yy.c y.tab.c -o output
./output

Running Python Implementations
python experiment1_lexer.py

Description:
Each experiment focuses on a specific phase of the compiler, demonstrating how programming constructs are analyzed, parsed, and translated.
This repository serves as a valuable resource for understanding compiler design principles through practical implementation.
   
