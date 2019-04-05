def start():
  print("Welcome to basic calculator")


  while True:
      try:

        num1 = int(input("Enter a number: "))
        op = input("Enter an operation: ")
        num2 = int(input("Enter another number: "))

        for operation in op:
          if operation == "+":
            print(f"The answer is : {num1 + num2}")
            break
          if operation == "-":
            print(f"The answer is : {num1 - num2}")
            break
          if operation == "*":
            print(f"The answer is : {num1 * num2}")
            break
          if operation == "/":
            print(f"The answer is : {num1 / num2}")
            break
          else:
            print("Invalid operation")
          
        
      except:
        print("Error")


start()
