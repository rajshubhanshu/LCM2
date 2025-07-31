def find_lcm(x, y):
    # Find the greater number
    if x > y:
        greater = x
    else:
        greater = y

    # Loop until we find a number divisible by both x and y
    while True:
        if greater % x == 0 and greater % y == 0:
            lcm = greater
            break
        greater += 1
    return lcm

# User input
num1 = int(input("Enter first number:\n"))
num2 = int(input("Enter second number:\n"))

# Calculate LCM
lcm = find_lcm(num1, num2)

# Output
print(f"LCM of {num1} and {num2} is: {lcm}")
