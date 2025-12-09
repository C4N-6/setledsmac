setleds: main.c main.h
	$(CC) -o $@ $< -framework Foundation -framework IOKit

.PHONY: clean all

clean :
	rm -f setleds

all : setleds

