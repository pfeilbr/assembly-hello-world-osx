## Description

Assembly code (NASM) for mac - hello world

## Build and run

	nasm -f macho hello.asm
	ld -e _start -o hello hello.o
	./hello
