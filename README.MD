# Object-Oriented Assembler

This project is an object-oriented version of the assembler I built while taking the Nand to Tetris course. It converts assembly language into binary code that a computer's CPU can execute. The code is organized into classes, making it easier to manage and expand.

### Features:

- **Symbol Resolution:** Handles labels and variables.
- **Code Generation:** Converts assembly instructions into binary code.
- **Modular Design:** Organized into classes for easier understanding and maintenance.

### Important Note:

This assembler **does not check for errors** or validate the assembly code. Make sure your code is correct before using this tool, as it will translate whatever you provide directly into machine code.

### Usage:

1. **Assembly File:** Place the assembly file you want to convert in the project folder.
2. **Execution:** Run the assembler and enter the name of your assembly file when prompted by the program.
3. **Output:** The binary file will be generated in the project folder with the same name as the assembly file, but with a `.bin` extension.

### Dependencies:

- Python 3.x
