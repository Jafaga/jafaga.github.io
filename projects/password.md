---
layout: project
type: project
image: img/pass.jpeg
title: "The Ultimate (not so really) Password Changer"
date: 2022
published: true
labels:
  - Python
  - Programming
  - Logical Thinking
  - Creaativity 
summary: "This Python program enhances password security by transforming user input through character replacements, capitalization, and symbol insertion, applying common password-strengthening practices."
---

<img width="300px" class="img-fluid" src="../img/password.jpeg">
<img width="500px" class="img-fluid" src="../img/Python-Logo.png">


This is a simple password enhancement program I wrote during my first year of college, and I was really proud of it. Python was the second programming language I learned, and this was one of the challenges I tackled. The program takes a word or phrase as input and transforms it into a more secure version by replacing certain characters with more secure or symbolic alternatives. For example, it changes the lowercase "a" to "@", "s" to "$", and "i" to "1". At the end, the program adds an exclamation mark to make the password even stronger. This basic form of password masking follows common security tips, like using symbols and numbers in passwords.

The logic of the program uses conditional statements and loops to go through each character in the input. It checks if certain characters are present and replaces them with predefined symbols. Plus, the first character is automatically capitalized to meet the common security rule of mixing uppercase and lowercase letters. The overall approach is simple but effective in transforming a basic string into a more secure format.

This project was a great way to learn how basic code can apply multiple security rules to an input string. The main goal is to enhance the security of whatever text the user provides, like a password, by swapping common letters with symbols or numbers. It’s a foundational exercise in string manipulation and applying security practices, which made it a useful learning project for me as a beginner in Python.

### Password Python Code

## Here is a sample Python code with input Mypassword:

<hr>

<pre><code>
# Get input from the user
word = input()

# Initialize an empty string to store the password
password = ''

# Convert the first character to uppercase
password += word[0].upper()

# Process the rest of the characters starting from index 1
for char in word[1:]:
    if char == 'm':
        password += 'M'
    elif char == 'i':
        password += '1'
    elif char == 'a':
        password += '@'
    elif char == 'B':
        password += '8'
    elif char == 's':
        password += '$'
    else:
        password += char

# Print the final password with an exclamation mark
print(password + '!')
</code></pre>

<hr>

The second code builds on the first one by expanding the range of character replacements, making the password even stronger. In addition to replacing "m," "i," "a," "B," and "s," this version also replaces "e" with "3," "o" with "0," "l" with "1," "t" with "7," and "g" with "9." This makes the password more complex by adding more substitutions, which helps improve security. The program still checks each character one by one, and when it finds a match, it replaces it with the corresponding symbol or number. Just like the first version, the final password also gets an exclamation mark at the end, which is another good practice for making passwords more secure.

This version makes the password even more secure by creating a bigger mix of symbols, numbers, and letters. It follows more security recommendations to make sure the password is harder to guess or break. Expanding the range of substitutions in this way gives the program a more comprehensive approach to password strengthening, making it a solid exercise in improving password security.

## Sample Python code taking the input of whatever password string the user inputs:

<pre><code>

# Get input from the user
word = input("Enter a word or phrase: ")

# Initialize an empty string to store the password
password = ''

# Process each character in the input
for char in word:
    if char == 'm':
        password += 'M'
    elif char == 'i':
        password += '1'
    elif char == 'a':
        password += '@'
    elif char == 'B':
        password += '8'
    elif char == 's':
        password += '$'
    elif char == 'e':
        password += '3'
    elif char == 'o':
        password += '0'
    elif char == 'l':
        password += '1'
    elif char == 't':
        password += '7'
    elif char == 'g':
        password += '9'
    else:
        password += char

# Print the final password with an exclamation mark
print(password + '!')

<hr>
