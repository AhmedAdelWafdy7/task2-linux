# task2-linux
Creating a femto shell and adding fib ,factand rand functions
\\ craeting main and function and headers code
\\\static
\\use commands : gcc -c fact.c fib.c headers.h
                 ar rcs libtask2.a fact.o fib.o headers.gch
                 gcc -c main.c
                 gcc -o prog main.o ./libtask2.a
                 
\\\dynamic 
\\use commands : gcc -shared -fpic -o libtask2.so fib.c fact.c headers.h
                 gcc -0 prog main.c ./libtask2.so
