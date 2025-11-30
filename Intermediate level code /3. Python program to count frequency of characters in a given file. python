filename = input("Enter file name: ")

freq = {}

with open(filename, "r") as f:
    data = f.read()

for ch in data:
    if ch in freq:
        freq[ch] += 1
    else:
        freq[ch] = 1

print("Character frequencies:")
for char, count in freq.items():
    print(f"{repr(char)} : {count}")
