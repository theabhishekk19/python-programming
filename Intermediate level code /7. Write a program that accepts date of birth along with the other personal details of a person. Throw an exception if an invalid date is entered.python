from datetime import datetime

try:
    name = input("Enter your name: ")
    age = input("Enter your age: ")
    dob = input("Enter your Date of Birth (DD-MM-YYYY): ")

   
    valid_date = datetime.strptime(dob, "%d-%m-%Y")

    print("\n--- Personal Details ---")
    print("Name:", name)
    print("Age:", age)
    print("Date of Birth:", valid_date.strftime("%d-%m-%Y"))

except ValueError:
    print("Invalid Date! Please enter the date in DD-MM-YYYY format.")
