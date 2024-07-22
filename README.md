- 👋 Hi, I’m @paarthbhatt
- 👀 I’m interested in learning new and creative methods of problem-solving.
- 🌱 I’m currently learning computer science engineering.
- 💞️ I’m looking to collaborate on various projects and assignments.
- 📫 How to reach me : 8920948990 or at paarthbhatt37@gmail.com
- 😄 Pronouns: he/him
- ⚡ Fun fact: I know how to pack a full 360 jab with my right fist so fast, you don't even see it coming.

<!---
paarthbhatt/paarthbhatt is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Function to add two numbers
def add(x, y):
    return x + y

# Function to subtract two numbers
def subtract(x, y):
    return x - y

# Function to multiply two numbers
def multiply(x, y):
    return x * y

# Function to divide two numbers
def divide(x, y):
    if y == 0:
        return "Error! Division by zero."
    else:
        return x / y

# Main function to operate the calculator
def calculator():
    print("Select operation:")
    print("1. Addition")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division")

    # Take input from the user
    choice = input("Enter choice (1/2/3/4): ")

    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))

    if choice == '1':
        print(num1, "+", num2, "=", add(num1, num2))
    elif choice == '2':
        print(num1, "-", num2, "=", subtract(num1, num2))
    elif choice == '3':
        print(num1, "*", num2, "=", multiply(num1, num2))
    elif choice == '4':
        print(num1, "/", num2, "=", divide(num1, num2))
    else:
        print("Invalid input")

# Call the calculator function
calculator()
