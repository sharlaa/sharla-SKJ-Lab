EXEC = add_numbers

SRC = add_numbers.cpp

all: $(EXEC)

$(EXEC): $(SRC)
	g++ -o $(EXEC) $(SRC)

dump: $(EXEC)
	objdump -d $(EXEC) > $(EXEC).asm

clean:
	rm -f $(EXEC) $(EXEC).asm

run: $(EXEC)
	./$(EXEC)
