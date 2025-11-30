import tempfile
import os

path = os.path.join(tempfile.gettempdir(), "mydata.txt")

file = open(path, "w")
file.write("Hello, this is a sample file.")
file.close()

file = open(path, "r")
data = file.read()
file.close()

print(data)
