# codehs
4.10.8: How Many Names?
# Your code below...
number_of_names = int(input("How many names do you have? "))
empty_cell = ""
for i in range(number_of_names):
    next = input("Enter names: ")
    empty_cell = empty_cell + " " + next
print empty_cell

