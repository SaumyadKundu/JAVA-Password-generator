# Password Generator

This Java program generates a random password based on user-specified criteria.

## Features

- Generates a password of a specified length.
- Allows the inclusion of numbers and/or special characters.
- Customizable password composition based on user input.

## Code Explanation

### Imports

- `Random` is used to generate random numbers for selecting characters.
- `Scanner` is used to take user input.

### Constants

- `UPPERCASE` contains uppercase letters.
- `LOWERCASE` contains lowercase letters.
- `DIGITS` contains numeric characters.
- `SPECIAL_CHARACTERS` contains special symbols.

### Main Method

- Prompts the user for the desired length of the password.
- Asks whether to include numbers and special symbols.
- Calls `generatePassword` to create the password based on user input.
- Displays the generated password.

### Generate Password Method

- Constructs the character set based on whether numbers and/or symbols are included.
- Uses `Random` to select characters from the character set.
- Assembles and returns the generated password as a `String`.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
