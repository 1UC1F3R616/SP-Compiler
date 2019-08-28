# SP-Compiler
🤖 Super Python Compiler

</br>

SP Compiler is a compiler that translates Py language into C language later to be compiled using gcc compiler, which ultimately gives us the machine code.

</br>

Even more it will be able to rectify identation error in *Py*.
So our intermediate form is *C* and the final output is machine code.

</br>

Compiled *C* code is 10 to 100(numeration, iterations) times faster then duplicate *Py* code.

</br>

Language processing system are kept general:
    
    Skeleton source program
            ⬇
    Pre processor
            ⬇
    Modified source program
            ⬇
    Compiler
            ⬇
    Target assembly program
            ⬇
    Assembler
            ⬇
    Rellocatable machine code
            ⬇
    Linked/loader
            ⬇
    Target machine code

</br>

Phases of compiler are kept general:

    Source program
        ⬇
    Lexical analysis
        ⬇
    Semantics analysis
        ⬇
    Intermediate code generator
        ⬇
    Code optimiser
        ⬇
    Code generator
        ⬇
    Target language

</br>
<h3>Basic Tasks</h3>


- [ ] Deciding correct datatypes (numbers, strings, lists, tuples, dictionary) --> (int, float, struct, union)
- [ ] conditionals--> if else
- [ ] loops --> for and while
- [ ] comments
- [ ] break and continue
- [ ] functions
- [ ] variable scopes
- [ ] file handling
- [ ] error handling (Exceptions) --> Secure calls

</br>

Making it to support all py libraries in indeed requires an industrial level work.

This project is for additional learning in Theory of compiler, from idea of project to it's devlopement has been done by Team D-E-F-E-A-T.

</br>

<h3>Project devlopment directions</h3>


> ♘ Devlopment of **Algorithm** to properly tokenize *Py* code and thus giving chunked *C* code.

> ♘ Basic Tasks

> ♘ Auto *Code optimization*

> ♘ Auto *Identation fixes*
