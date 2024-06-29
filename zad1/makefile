myProgram: main.o employee.o address.o
	g++ $+ -o $@

%.o: %.cpp
	g++ -c $<

main.o: employee.h address.h

employee.o: address.h
