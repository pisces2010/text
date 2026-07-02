string = input("Please enter a string: ")

string2 = ('')
# Reverse the string
for i in string:
    string2 = i + string2

print("\n Original string is:", string)
print("The reversed string is:", string2)
