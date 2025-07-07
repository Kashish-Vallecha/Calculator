# 🧮 Basic Console Calculator
A simple, interactive console-based calculator. It also allows users to perform basic arithmetic operations.

   
# Basic calculator uses:
- Add
- Subtract
- Multiply
- Divide
- Exit Choose an operation (1-5):
- 1 Enter first number: 5
- Enter second number: 3
- Result: 8.0
  



 
 ## 🚀 Features
- It uses characters like +, -, *, /.
- Four fundamental operations: Add, Subtract, Multiply, Divide  
- Input validation to ensure numeric entries  
- Division-by-zero error handling  
- Continuous loop until user chooses to exit  
- Clean, user-friendly interface

## 🔧 How to Use
 **Follow the menu prompt** in the terminal:
   - Enter a choice from the menu (1–5).
   - Input two numbers for the operation.
   - View the result and repeat or exit.

## Python Specifications used are:
1. Function Definitions -  def,
2. Infinite Loop with while True
3. User Input With  input()
choice = input("Choose an operation (1-5): ")
4. Type Conversion.
 float() is used to ensure inputs can represent both integers and decimals.
5.  Conditional Logic with if-elif-else
if choice == '1':
    print(f"Result: {add(num1, num2)}")
6. . Formatted Strings (f-strings)
7.  Exception Handling with try-except
try:
    num1 = float(...)
except ValueError:
    print("Invalid input!")
8. Program Entry Point Check
if __name__ == "__main__":
    main()
   - Ensures the script runs only when executed directly, not when imported as a module.








  







