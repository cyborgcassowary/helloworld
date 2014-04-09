Learning C - Hello World

URL of Tutorial: http://www.buildyourownlisp.com/chapter2_installation

Common Terminal commands for C:

1. Checks the version of C you're running:

cc --version


2. Hello world file;

#include <stdio.h>

int main(int argc, char** argv) {
  puts("Hello, world!");
  return 0;
}


stdio.h - the standard input and output library which comes included with C

puts is included in stdio.h library

Next we declare a function called main. This function is declared to output an int, and take as input an int called argc and a char** called argv. All C programs must contain this function. All programs start running from this function.

Inside main the puts function is called with the argument "Hello, world!". This outputs the message Hello, world! to the command line. The function puts is short for put string. The second statement inside the function is return 0;. This tells the main function to finish and return 0. When a C program returns 0 this indicates there have been no errors running the program.



Next! Produce the actual executable file with this line in the terminal: 

cc -std=c99 -Wall hello_world.c -o hello_world




Badda bing, badda boom! My first C file.

~ Ryan Hettler