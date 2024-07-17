# PAN Card Generator

This project is a simple PAN card generator written in Java. It takes a user's name as input and generates a unique PAN card number based on specific rules. The generated PAN card number consists of a combination of random letters, the first letter of the user's name, random digits, and a final letter determined by the generated digits.

## How it works

1. The program takes the user's name as input.
2. It generates a random string of 4 letters.
3. It generates a random string of 4 digits.
4. The first letter of the user's name is included in the PAN card number.
5. A final letter is determined based on the value of the generated digits.
6. The program checks for uniqueness and ensures the generated PAN card number is not repeated.
7. It outputs the generated PAN card number.

## Requirements

- Java Development Kit (JDK) 8 or higher

## How to run the project

1. Clone the repository or download the source code files.
2. Open the terminal/command prompt and navigate to the directory where the files are located.
3. Compile the Java file using the following command:
4. Run the compiled Java program using the following command:
5. Enter the user's name when prompted.
6. The generated PAN card number will be displayed.

## Example


## Code Explanation

The main components of the code are:

- `generate(String word)`: This method generates a PAN card number based on the user's name.
- It creates a random string of letters and digits, includes the first letter of the user's name,
- and appends a final letter based on the generated digits.
- `main(String[] args)`: This method is the entry point of the program.
- It takes the user's input, calls the `generate` method to create the PAN card number,
- ensures the number is unique, and displays the result.
