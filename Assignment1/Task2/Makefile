all: asm_to_cpp

asm_to_cpp: asm_to_cpp.cpp
	g++ -o asm_to_cpp asm_to_cpp.cpp

dump: asm_to_cpp
	objdump -d asm_to_cpp > asm_to_cpp.asm

clean:
	rm -f asm_to_cpp asm_to_cpp.asm

run: asm_to_cpp
	./asm_to_cpp