FizzBuzz Freestanding Edition
==============================

![FizzBuzz Freestanding Screenshot](docs/img/fizzbuzz-freestanding-edition.gif)

[FizzBuzz](https://en.wikipedia.org/wiki/Fizz_buzz) is a common interview question for computer programmers. Creating a list of the first 100 Fizz buzz numbers is a trivial problem for any would-be computer programmer, so interviewers can easily sort out those with insufficient programming ability. -- Wikipedia.

[Freestanding](http://wiki.osdev.org/C_Library#Freestanding_and_Hosted) is a C compilation environment where only a few headers are usable that contains only defines and types. Usually program is compiled in hosted environment, which is meant for user-space programming while freestanding is meant for kernel programmingr

Freestanding program runs without operating system, therefore it can not do system call. Actually, the program itself is the only running program in the machine.


## Credits

- boot loader and vga driver are derived from [http://wiki.osdev.org/Bare_Bones](http://wiki.osdev.org/Bare_Bones)
- `itoa` implementation by by Lukás Chmela
