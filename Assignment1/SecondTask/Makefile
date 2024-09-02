all: 
	equivalent_assembly_code
equivalent_assembly_code: 
	equivalent_assembly_code.cpp
	g++ -o equivalent_assembly_code equivalent_assembly_code.cpp
dump: 
	equivalent_assembly_code
	objdump -d equivalent_assembly_code > equivalent_assembly_code.asm
clean:
	rm -f equivalent_assembly_code equivalent_assembly_code.asm
run: 
	equivalent_assembly_code
	./equivalent_assembly_code