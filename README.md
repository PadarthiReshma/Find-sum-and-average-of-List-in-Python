# Find-sum-and-average-of-List-in-Python

# Apporach-1
# Python program to find the sum and average of the list
L = [4, 5, 1, 2, 9, 7, 10, 8]

# variable to store the sum of the list
count = 0
# Finding the sum
for i in L:
	count += i

# divide the total elements by number of elements
avg = count/len(L)

print("sum = ", count)
print("average = ", avg)

# Apporach-2

# Python program to find the sum and average of the list
L = [4, 5, 1, 2, 9, 7, 10, 8]
# using sum() method
count = sum(L)

# finding average
avg = count/len(L)

print("sum = ", count)
print("average = ", avg)

# Apporach-3
 # Using sum() and statistics.mean() 
# Python program to find the sum and average of the list

import statistics
L = [4, 5, 1, 2, 9, 7, 10, 8]
# using sum() method
sum1 = sum(L)

# finding average
avg = statistics.mean(L)

print("sum = ", sum1)
print("average = ", avg)

