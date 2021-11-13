nasm:
	nasm -f elf64 *.s

compile-mem: nasm
	gcc -g3 -Wextra -Wall -std=c99 -pedantic -fsanitize=address *.c *.o

compile: nasm
	gcc -g3 -Wextra -Wall -std=c99 -pedantic *.c *.o

run:
	./a.out

debug: compile
	gdb -tui ./a.out

