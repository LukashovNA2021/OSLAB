all: server1 client client2

server: server1.c common.h
	gcc server1.c -o server1

client: client.c common.h
	gcc client.c -o client
	gcc client2.c -o client2

clean:
	-rm server1 client *.o
