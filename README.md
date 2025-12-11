# Tuples-and-built-in-functions
numbers = (10, 20, 30, 40, 50, 20)
print("Original Tuple:", numbers)


print("First element:", numbers[0])
print("Last element :", numbers[-1])


print("Tuple slice (index 1 to 4):", numbers[1:5])


print("Count of 20:", numbers.count(20))


print("Index of 40:", numbers.index(40))


print("Length of tuple:", len(numbers))


print("Maximum value:", max(numbers))
print("Minimum value:", min(numbers))
print("Sum of tuple elements:", sum(numbers))


new_tuple = numbers + (60, 70, 80)
print("After concatenation:", new_tuple)

OUTPUT:

Original Tuple: (10, 20, 30, 40, 50, 20)
First element: 10
Last element : 20
Tuple slice (index 1 to 4): (20, 30, 40, 50)
Count of 20: 2
Index of 40: 3
Length of tuple: 6
Maximum value: 50
Minimum value: 10
Sum of tuple elements: 170
After concatenation: (10, 20, 30, 40, 50, 20, 60, 70, 80)
Repeated Tuple: (10, 20, 30, 40, 50, 20, 10, 20, 30, 40, 50, 20)
