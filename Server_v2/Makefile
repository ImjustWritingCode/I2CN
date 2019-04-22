.PHONY: rm

all: svr cli

svr: server.c
	gcc server.c -o svr.out

cli: client.c
	gcc client.c -o cli.out

clean:
	rm -rf server
	rm -rf client

rm:
	rm -rf ./download/*
