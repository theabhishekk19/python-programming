class NameErrorException(Exception):
    pass

try:
    name = input("Enter your name: ")

    if name == "Rahul":
        raise NameErrorException("Access denied! Please quit the program.")

    print("Hello,", name)

except NameErrorException as e:
    print(e)
