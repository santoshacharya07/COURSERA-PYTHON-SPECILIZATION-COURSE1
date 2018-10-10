# COURSERA-PYTHON-SPECILIZATION-COURSE1


largest = None
smallest = None

while True:
    number = input("Please enter a number ")
    if (number == "done"): break
    elif(True):
        try:
            number = int(number)
        except:
            print("Invalid input")
            continue
    if (largest is None or number > largest):  largest = number
    elif (smallest is None or number < smallest) : smallest = number


print("Maximum is", largest)
print("Minimum is", smallest)
