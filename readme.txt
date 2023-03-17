Division 3.0

Two numbers given as arguments are divided and the result will be shown in 
the terminal.

The first given number will be divided by the second given number.

The new feature is that the numbers to be multiplied together can be given as
arguments at the command line when the program is invoked.

It will be assumed that the name of the program file after compilation will be

  divide
  
If you chose a different name please use this one instead of "divide".


Just invoke like

  ./divide number1 number2

for example

  ./divide 5.80 6.95

And the result will be shown on the terminal.

The numbers are represented as double- values.

If too few arguments are given, the program aborts without telling a result.

The interactive mode that enabled entering the numbers after invocation with
"in: " prompts got removed because the division of two numbers certainly is 
not regarded as a big task and it was considered more comfortable to pass 
the two numbers just at the invocation.



Version history:
----------------

Version 3.0:

Implementation of data entry by giving arguments at invocation.


Version 2.0:

Implementation of full user interaction to make the program operatable without the usage of a debugger.



Version 1.0:

Initial version.

