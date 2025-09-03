# fundamentala-project
# Fundamental Booster Project

# Welcome message
print("Welcome to the Personal Data Collector!")
print("This program will collect and display your personal information.\n")

# Collecting Information
name = input("Please enter your name: ")
age = int(input("Please enter your age: "))
height = float(input("Please enter your height (in meters): "))
weight = float(input("Please enter your weight (in kg): "))
fav_number = int(input("Please enter your favorite number: "))

print("\nThank you! Processing your information...\n")

# Type casting and ensuring correct types
age = int(age)
height = float(height)
weight = float(weight)
fav_number = int(fav_number)

# id() and type() usage
print("=== Variable Summary ===")
print(f"Name: {name}, Type: {type(name)}, ID: {id(name)}")
print(f"Age: {age}, Type: {type(age)}, ID: {id(age)}")
print(f"Height: {height}, Type: {type(height)}, ID: {id(height)}")
print(f"Weight: {weight}, Type: {type(weight)}, ID: {id(weight)}")
print(f"Favorite Number: {fav_number}, Type: {type(fav_number)}, ID: {id(fav_number)}")

# Data Processing (Simple Calculation)
birth_year = 2025 - age
bmi = weight / (height ** 2)

print("\n=== Processed Information ===")
print(f"Hello {name}, here are your details:")
print(f"- You are {age} years old (born around {birth_year}).")
print(f"- Your height is {height} meters and your weight is {weight} kg.")
print(f"- Your BMI is approximately {bmi:.2f}")
print(f"- Your favorite number is {fav_number}.")

# Exit message
print("\nThank you for using the Personal Data Collector. Goodbye!")
