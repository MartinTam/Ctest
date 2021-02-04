# Ctest

This bash script is used for comparing the output from the program written in C with the correct output.

# Why I wrote this?

I needed to automate the testing process, while I was doing my homeworks in the subject PA1 (Programming and algorithmic 1

) at [FIT CTU Prague](https://fit.cvut.cz/cs).

# How to use it:

  1. Put this script inside the directory next to your program and the compiled file of your program.
  
  2. Make sure that inside this directory there is another directory called 'data', where you've got all your
     correct input and output files with the same name and ending with either '.in' or '.ref'.
     
  3. Execute this script with the compiled file of your program as an argument.
  
# Example

    bash Ctest.sh compiledFile.out

# How it looks like:

![Screenshot](/images/screenshot.png)

# License

The code is available under the [MIT](https://github.com/MartinTam/Ctest/blob/master/LICENSE) license.
