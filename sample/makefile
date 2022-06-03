COMMON = -O2 -I../include -L../bin
LDFLAGS = -lglfw.3.3 -lmujoco.2.2.0
CC = gcc
ROOT = -o ../bin/main
CFLAGS = -c -w

all: main_all

main_all: main.o
	$(CC) $(COMMON) $(LDFLAGS) $(ROOT) main.o
main.o: main.c
	$(CC) $(COMMON) $(CFLAGS) main.c
clean:
	rm main.o
