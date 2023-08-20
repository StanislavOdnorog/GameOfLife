CC=gcc
FLAGS= -Wall -Werror -Wextra -std=c11 -lncurses
SRC=main.c
OUT=../build/GameOfLife
DATA=./data.txt



build:
	$(CC) $(FLAGS) $(SRC) -o $(OUT)

run:
	$(OUT) < $(DATA)
