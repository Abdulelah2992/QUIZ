SRC = main.c math/src/math.c utils/src/utils.c io/src/io.c extra/src/extra.c

OBJ = bulid/main.o bulid/math.o bulid/utils.o bulid/io.o bulid/extra.o


CC = gcc


compile: 
	@mkdir -p build
	$(CC) -o build/AAA $(SRC) 

clean:
	rm -rf bulid

help:
	@echo "clean-remove build files "
	@echo "compile-compile the project"
	@echo "help-display this help messag"

