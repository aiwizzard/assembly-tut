# assembly-tut  

## Convert assembly source file to executable object file  
`as assem.s -o assem.o`  


## Compile the object file  
`gcc -o assem assem.o -nostdlib -static`  


## Run the executable  
`./assem`
