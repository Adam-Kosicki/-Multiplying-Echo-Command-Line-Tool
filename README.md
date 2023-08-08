# -Multiplying-Echo-Command-Line-Tool
C | Command-Line Arguments, Data Conversion, Flow Control, Error Handling

## Functionality

- The program accepts command-line options to specify starting value (`-s`), repeat count (`-n`), and a multiplier.
- It processes the options using `getopt` and converts them to appropriate numeric values.
- If the `-s` option is provided, the program prints the starting value to the standard output and error output.
- The program then enters a loop that reads user-input values from the standard input.
- For each input value, it multiplies the value by the specified multiplier and prints the result to the standard output and error output.
- The loop iterates as many times as specified by the repeat count.
- If the input value is not a valid number, it ignores the input.
- The program terminates when it finishes processing all input or when an invalid option or insufficient arguments are provided.

The code is well-commented, explaining its purpose, how the options are processed, and the logic behind printing values to the output.
