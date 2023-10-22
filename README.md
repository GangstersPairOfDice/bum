bum is a text editor written in C originally based on [antirez’s kilo](http://antirez.com/news/108), guided by [Build Your Own Text Editor](https://viewsourcecode.org/snaptoken/kilo/)

# Usage

C is a compiled language. That means we need to run our program through a C compiler to turn it into an executable file. We then run that executable like we would run any other program on the command line.

## Compiling with `cc` (Clang)

To compile bum.c, run `cc bum.c -o bum` in your terminal shell. If no errors occur, this will produce an executable named `bum`. `-o` stands for “output”, and specifies that the output executable should be named `kilo`.

## Compiling with `make`

Typing `cc bum.c -o bum` every time you want to recompile gets tiring. The `make` program allows you to simply run `make` and it will compile the program for you.

## Running `bum`

After compiling, to run `bum`, type `./bum` in your terminal shell and Enter/Return.
