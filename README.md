# ASM template

## How to use ?
```bash
 wget https://github.com/valimero/template-asm/archive/refs/heads/master.zip && \
    unzip master.zip && \
    mv template-asm-master/template/* . && \
    rm -rd master.zip template-asm-master
```

## What does that script ?
- add a Makefile in yout current directory
- add a main.c 


## Command
- `make compile`	--> compile all .s code and .c
- `make run` 		--> run main.c
- `make clean`		--> clean *.out and *.c	
