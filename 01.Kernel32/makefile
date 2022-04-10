
all: Kernel32.bin

Kernel32.bin: Source/EntryPoint.s
	nasm -o Kernel32.bin $<
	
claen:
	rm -f Kernel32.bin
	
	