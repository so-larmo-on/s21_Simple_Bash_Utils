CC=gcc
CFLAGS=-Wall -Werror -Wextra

all: clean rebuild

rebuild: s21_cat

s21_cat: clean
	$(CC) $(CFLAGS) s21_cat.c -o s21_cat

clean:
	rm -rf s21_cat