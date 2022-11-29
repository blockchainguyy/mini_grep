Rust_CLI_GREP

This program takes an input string and path to a file and 
checks for that string in the file and prints the lines 
those contains the specified words.

Things covered
* Read command line inputs
* printing arguments read from command
* reading a file
* searching for string in file contents
* matching the string for case_sensitive data and printing
 accordingly

 Run the program
 * cargo run <alpha> poem.txt
 where alpha: word you want to search in file "poem.txt"

 to read case insensitive data,
 * export CASE_INSENSITIVE = true
 * cargo run <alpha> poem.txt

 for case sensitive data,
 * unset CASE_INSENSITIVE
 * cargo run <alpha> poem.txt

 To print the output in file <output.txt>
* cargo run <alpha> poem.txt > output.txt

We're getting the output in the file "output.txt" and
errors in the terminal.