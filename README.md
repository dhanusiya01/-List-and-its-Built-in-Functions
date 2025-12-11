# -List-and-its-Built-in-Functions
 numbers = [10, 20, 30, 40, 50]
print("Original List:", numbers)

numbers.append(60)
print("After append(60):", numbers)

numbers.insert(1, 15)
print("After insert(1, 15):", numbers)

numbers.remove(30)
print("After remove(30):", numbers)

numbers.pop(2)
print("After pop(2):", numbers)

numbers.extend([70, 80])
print("After extend([70, 80]):", numbers)

print("Count of 20:", numbers.count(20))
print("Index of 50:", numbers.index(50))

numbers.sort()
print("After sort():", numbers)

numbers.reverse()
print("After reverse():", numbers)

copy_list = numbers.copy()
print("Copied List:", copy_list)

print("Length of list:", len(numbers))

print("Maximum value:", max(numbers))
print("Minimum value:", min(numbers))
print("Sum of list:", sum(numbers))

numbers.clear()
print("After clear():", numbers)


OUTPUT:

Minimum value: 10
Sum of list: 325
After clear(): []
Original List: [10, 20, 30, 40, 50]
After append(60): [10, 20, 30, 40, 50, 60]
After insert(1, 15): [10, 15, 20, 30, 40, 50, 60]
After remove(30): [10, 15, 20, 40, 50, 60]
After pop(2): [10, 15, 40, 50, 60]
After extend([70, 80]): [10, 15, 40, 50, 60, 70, 80]
Count of 20: 0
Index of 50: 3
After sort(): [10, 15, 40, 50, 60, 70, 80]
After reverse(): [80, 70, 60, 50, 40, 15, 10]
Copied List: [80, 70, 60, 50, 40, 15, 10]
Length of list: 7
Maximum value: 80
