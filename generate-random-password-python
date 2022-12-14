import random
import string

def generate_password(length, num_passwords):
  # Create a list of all possible characters for the password
  # This includes lowercase letters, uppercase letters, and digits
  characters = string.ascii_lowercase + string.ascii_uppercase + string.digits

  # Generate the specified number of passwords
  for i in range(num_passwords):
    # Start with an empty password
    password = ""

    # Add a random character from the list of possible characters to the password
    # Repeat this process until the password is the desired length
    for j in range(length):
      password += random.choice(characters)

    # Print the generated password
    print(password)

# Prompt the user for the password length and number of passwords to generate
length = int(input("Enter the password length: "))
num_passwords = int(input("Enter the number of passwords to generate: "))

# Generate the passwords using the user-specified length and number
generate_password(length, num_passwords)
