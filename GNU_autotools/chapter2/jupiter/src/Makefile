all: jupiter

jupiter: main.c
	@sources=bar.c; echo $${sources}
	@#gcc -g -O0 -o $@ ${sources}

clean:
	-rm jupiter
.PHONY: all clean
