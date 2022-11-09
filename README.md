# ARM Assembly Homework



Type in the first assembly program from the [Raspberry Pi Assembler](https://comp264.org/readings/RPiA.pdf) book in section 1.3, page 10 of the PDF. Compile the program on x86 Ubuntu with:

    arm-none-linux-gnueabi -static -o first first.s

Or use whatever cross compiler is on your system.

Run the program with:

    qemu-user ./first
    echo $?

Submit in your GitHub repository:

1. Your source code `first.s`
2. A screenshot of your terminal compiling and running your program
