CC = gcc
CC_FLAGS = -Wall -g

all: test hashTable.o

hashTable.o: hashTable.c hashTable.h
	$(CC) $(CC_FLAGS) -c hashTable.c
	
test: test.c
	$(CC) $(CC_FLAGS) -o test test.c







