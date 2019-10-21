# Ctest

This bash script is use for comparing the output, from the program written in C, with the correct output.

How to use it:

	a)	Put this script inside the directory next to your program and the compiled file of your program.

	b)	Make sure, that inside this directory there is another directory called 'data',
		where you`ve got all your correct input and output files with the same name and ending
		with either '.in' or '.ref'.

	c)	Execute this script with the compiled file of your program as an argument.

	d)	Example: bash Ctest.sh compiledFile.out

Created by Martin Tam in 2019.
