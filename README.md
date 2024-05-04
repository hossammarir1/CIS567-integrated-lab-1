# CIS567-integrated-lab-1
contains materials related to a computer science or information systems course
def print_incremented_values(num1, num2):
    if num2 < num1:
        print("Second integer can't be less than the first.")
    else:
        while num1 <= num2:
            print(num1, end=' ')
            num1 += 5
        print()

num1 = int(input())
num2 = int(input())

print_incremented_values(num1, num2)
