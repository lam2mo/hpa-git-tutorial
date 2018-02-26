TARGETS=hello

all: $(TARGETS)

hello: hello.c
	gcc -g -O2 -std=c99 -Wall -pedantic -o $@ $<

clean:
	rm -f $(TARGETS)

