# Fundamental Booster

A small interactive Python script that collects basic personal data from the user, prints each value along with its type and memory address, and estimates the user's birth year.

## What it does

1. Prompts the user for:
   - Name
   - Age
   - Height (in meters)
   - Favourite number
2. Prints each collected value together with its Python type and id (memory address).
3. Calculates an approximate birth year based on the current year (2026) and the entered age.
4. Prints a farewell message.

## Requirements

Python 3.x. No external libraries needed.

## Usage

Run the script from a terminal using: python fundamental_booster.py

You will be prompted to enter your name, age, height, and favourite number in turn. The script will then display the collected information and your estimated birth year.

## Example

When run, the script greets the user, asks for name, age, height, and favourite number, then echoes back each value with its type and memory address, followed by an estimated birth year and a goodbye message.

## Known issues

- The birth year message contains a hardcoded phrase "(based on your age of 17)" regardless of the age actually entered — this looks like a leftover placeholder and likely needs to be updated to reference the user's actual age.
- Memory addresses (id()) are implementation details of CPython and will vary between runs; they're printed here for educational purposes only.
- No input validation — non-numeric input for age, height, or favourite number will raise an exception.
  
connect to me:
linkdin = www.linkedin.com/in/nisha-sonkusre-283526415
email = nishasonkusre07@gmail.com
