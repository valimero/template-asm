compile:
	nasm -f elf64 *.s
	gcc -g3 -Wextra -Wall -std=c99 -pedantic -fsanitize=address *.c *.o 

run:
	./a.out


clean:
	rm ./a.out *.o
    
