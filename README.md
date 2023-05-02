# Email Validation Program
This is a simple email validation program written in Python. It prompts the user to enter an email address and checks whether the email address is valid according to a regular expression pattern. <br /><br /><br />

# Usage
To use this program, simply run the Python script and enter an email address when prompted. The program will then check whether the email address is valid and print either "Correct Email" or "Wrong Email" depending on the result.<br /><br />

# How it works
The program uses a regular expression pattern to check whether the email address is valid. The pattern is defined as follows:<br /><br />


# Copy code

```

email_condition = "^[a-z]+[\._]?[a-z 0-9]+[@]\w+[.]\w{2,3}$"

```
<br />

This pattern checks whether the email address starts with one or more lowercase letters, followed by an optional period or underscore, followed by one or more lowercase letters or numbers, followed by an "@" symbol, followed by one or more alphanumeric characters, followed by a period and two or three letters.

The program then uses the re.search() function to check whether the user-provided email address matches the pattern. If it does, the program prints "Correct Email". If it does not, the program prints "Wrong Email".
<br /><br /><br />
# Conclusion
This program demonstrates a simple approach to email validation in Python using regular expressions. It could be useful for anyone who needs to validate user-provided email addresses in their Python applications.