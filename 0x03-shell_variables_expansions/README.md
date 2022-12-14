# 0x03. Shell, init files, variables and expansions

## Learning Objectives
### General
* What happens when you type $ ls -l *.txt

### Shell Initialization Files
* What are the /etc/profile file and the /etc/profile.d directory
* What is the ~/.bashrc file

### Variables
* What is the difference between a local and a global variable
* What is a reserved variable
* How to create, update and delete shell variables
* What are the roles of the following reserved variables: HOME, PATH, PS1
* What are special parameters
* What is the special parameter $??

### Expansions
* What is expansion and how to use them
* What is the difference between single and double quotes and how to use them properly
* How to do command substitution with $() and backticks

### Shell Arithmetic
* How to perform arithmetic operations with the shell

### The alias Command
* How to create an alias
* How to list aliases
* How to temporarily disable an alias

### More Info
* Read your /etc/profile, /etc/inputrc and ~/.bashrc files.

| Filename | Description |
| -------- | ----------- |
| [0-alias](0-alias) | creates an alias. <br> name: `ls` <br> value: `rm *` |
| [1-hello_you](1-hello_you) | prints `hello user`, where user is the current Linux user. |
| [2-path](2-path) | adds `/action` to the `PATH`. `/action` will be the last directory the shell looks into when looking for a program. |
| [3-paths](3-paths) | counts the number of directories in the `PATH`. |
| [4-global_variables](4-global_variables) | lists the environment variables. |
| [5-local_variables](5-local_variables) | lists all local variables and environment variables, and functions. |
| [6-create_local_variable](6-create_local_variable) | creates a new local variable. <br> name: BEST <br> value: School |
| [7-create_global_variable](7-create_global_variable) | creates a new global variable. <br> name: BEST <br> value: School |
| [8-true_knowledge](8-true_knowledge) | prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE` |
| [9-divide_and_rule](9-divide_and_rule) | prints the result of `POWER` divided by `DIVIDE`. |
| [10-love_exponent_breath](10-love_exponent_breath) | displays the result of `BREATH` to the power `LOVE` |
| [11-binary_to_decimal](11-binary_to_decimal) | converts a number from base 2 to base 10. <br> number in base 2 is stored in the environment variable BINARY |
| [12-combinations](12-combinations) | prints all possible combinations of two letters, except oo. <br> letters are lower cases, from `a` to `z` <br> one combination per line <br> output is alpha ordered, starting with `aa` <br> does not print `oo` <br> script contains maximum 64 characters |
| [13-print_float](13-print_float) | prints a number with two decimal places |
| [100-decimal_to_hexadecimal](100-decimal_to_hexadecimal) | converts a number from base 10 to base 16. <br> number is in base 10 and stored in the environment variable DECIMAL <br> script displays the number in base 16 |
| [101-rot13](101-rot13) | encodes and decodes text using the rot13 encryption. Assume ASCII. |
| [102-odd](102-odd) | prints every other line from the input, starting with the first line. |
| [103-water_and_stir](103-water_and_stir) | adds the two numbers stored in the environment variables WATER and STIR and prints the result. <br> WATER is in base water <br> STIR is in base stir. <br> The result should be in base bestchol |
