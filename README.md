# Tuples-and-Lists

#Tuples: A tuple is a sequence of arbitrary objects separated by commas and enclosed in 
parentheses. If the tuple contains a single object, a final comma is required; for 
example, x = (2,). Tuples support the same operations as strings; they are also 
immutable (cannot be changed after declaration).

# Store input Tuples

A = (10, “a”, “Name”, 2*4)
print(A)
print(A[2])

# Output of A

(10, ‘a’, ‘Name’, 8)
Name

#Lists: A list is similar to a tuple, but it is mutable, so that its elements and length can be 
changed. A list is identified by enclosing it in brackets.

# Store input Lists

L = [5, “k”, “Name”, 1+5]
print(L)
L.append(9)
print(L)
L.pop(2)
print(L)

# Output of L

[5, ‘k’, ‘Name’, 6]
[5, ‘k’, ‘Name’, 6, 9]
[5, ‘k’, 6, 9]
