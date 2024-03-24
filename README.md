# Kitty Ipsum Translator 

*Learning Documentation*

This project was developed as part of the **Learn Advanced Bash by Building a Kitty Ipsum Translator** course, which is included in the [Relational Database](https://www.freecodecamp.org/learn/relational-database/) certification from freeCodeCamp. The course consists of **140 lessons**, during which I learned about more complex commands and the details of how these commands work.

## Learning Outcomes

### Complex Commands

The `complex-commands.md` file contains examples of the complex commands learned during the course. These include:

- `wc`: This command is used to count the number of lines, words, and characters in a file. For example, `wc -l kitty_ipsum_1.txt` was used to count the number of lines in the `kitty_ipsum_1.txt` file.

- `grep`: This command is used to search for specific patterns in a file. For example, `grep -o 'meow[a-z]*' kitty_ipsum_1.txt | wc -l` was used to count the number of times 'meow' or 'meowzer' appears in the `kitty_ipsum_1.txt` file.

- `sed`: This command is used for text substitution. For example, `sed -E 's/([0-9]+).*/\1/'` was used to extract the line numbers where 'meow' or 'meowzer' appears in the `kitty_ipsum_1.txt` file.

### Scripting

The `translate.sh` script demonstrates the application of these commands in a practical context. This script translates 'kitty ipsum' text into 'doggy ipsum' text by replacing 'catnip' with 'dogchow', 'cat' with 'dog', and 'meow' or 'meowzer' with 'woof'. This is achieved using the `cat` command to read the input file and the `sed` command to perform the text substitutions.

### Command Outputs
If you wish to see the outputs of the commands used in this project, please refer to the [command-outputs.md](bash-complex-commands%2Fcomplex-commands.md) file. This file contains the results of executing the complex commands and scripts discussed in this documentation.

## Conclusion

This course provided a comprehensive introduction to advanced Bash scripting, including the use of complex commands and the creation of practical scripts. The knowledge and skills gained from this course will be invaluable for future projects and professional development.