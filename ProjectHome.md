Example of the functionality of Maximal Munch on a simple compiler.

With an AST and a cost table of instructions, it will apply the maximal munch algorithm and determin the cost of the expression.

The AST and Instructions are hard-coded on the project.

The program is a command-line java aplication. Run with the java -jar command.

When running, choose an expression and it will show you information about the possible instructions.
Then it will use the Maximal Munch algorithm to choose the instructions for that tree.

In the end it will show the instructions, the level of the tree where they occur and the cost of that instruction. Then show the total cost of the chosen AST.