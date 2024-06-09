
SERVER_NAME = server.out 
PORT = 8080 

all: main.c
	gcc -o $(SERVER_NAME) main.c -lfcgi

start_server:
	spawn-fcgi -p $(PORT) $(SERVER_NAME)