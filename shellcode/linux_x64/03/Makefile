shellcode:shellcode.o
	ld -o shellcode shellcode.o
shellcode.o:
	nasm -f elf64 shellcode.asm
clean:
	rm ./shellcode.o
	rm ./shellcode
