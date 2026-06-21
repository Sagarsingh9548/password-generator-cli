# password-generator-cli
A simple Python CLI application that generates secure random passwords using uppercase letters, lowercase letters, numbers, and special characters.
## Overview

This is a simple Password Generator built using Python. It generates a random password based on the length entered by the user.

The generated password contains a combination of:
- Uppercase letters (A-Z)
- Lowercase letters (a-z)
- Numbers (0-9)
- Special characters (!, @, #, $, %, etc.)

This helps create strong and secure passwords for different applications.

## Features

- User-defined password length
- Random password generation
- Includes uppercase and lowercase letters
- Includes numbers
- Includes special characters
- Easy to use through the command line

## How It Works

1. The user enters the desired password length.
2. The program creates a pool of characters containing:
   - Uppercase letters
   - Lowercase letters
   - Digits
   - Special characters
3. Using Python's `random` module, random characters are selected from the pool.
4. The selected characters are combined to form a password.
5. The generated password is displayed on the screen.

## Main Functions Used

### random.choice()
Selects a random character from the available character set.

### string.ascii_uppercase
Provides all uppercase letters (A-Z).

### string.ascii_lowercase
Provides all lowercase letters (a-z).

### string.digits
Provides digits from 0 to 9.

### string.punctuation
Provides special characters such as !, @, #, $, %, etc.
