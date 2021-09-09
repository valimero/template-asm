# ASM template

## How to use ?


### Download from github
```bash
 wget https://github.com/valimero/template-asm/archive/refs/heads/master.zip && \
    unzip master.zip && \
    mv template-asm-master/template/* . && \
    rm -rd master.zip template-asm-master
```

### Offline command
```bash
echo "int main(int arg, char **argv)
{
    return 0;
}" > main.c && echo "compile:
	nasm -f elf64 *.s
	gcc *.c *.o

run:
	./a.out


clean:
	rm ./a.out *.o
" > Makefile
```

## What does that script ?
- add a Makefile in yout current directory
- add a main.c 


## Command
- `make compile`	--> compile all .s code and .c
- `make run` 		--> run main.c
- `make clean`		--> clean *.out and *.c	
