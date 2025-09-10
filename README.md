# IS-Lab-Assign
Assignment
list1 = [int(x) for x in input("Enter numbers for first list  ").split()]
list2 = [int(x) for x in input("Enter numbers for second list : ").split()]

merged = list1 + list2   
merged.sort()            

print("Merged and Sorted List:", merged

Task 2

list1 = [int(x) for x in input("Enter numbers for first list : ").split()]
list2 = [int(x) for x in input("Enter numbers for second list : ").split()]

merged = list1 + list2
print("Smallest number is:", min(merged))
print("Largest number is:", max(merged))

Task 3

birthdays = {
    "Albert Einstein": "03/14/1879",
    "Benjamin Franklin": "01/17/1706",
    "Ada Lovelace": "12/10/1815"
}

print("Welcome to the birthday dictionary. We know the birthdays of:")
for name in birthdays:
    print(name)

person = input("Whose birthday do you want to look up? ")

if person in birthdays:
    print(person,"'s birthday is", birthdays[person])
else:
    print("Sorry, I don't know that person.")

    Task 4
    sample_dict = {
    "name": "Kelly",
    "age": 25,
    "salary": 8000,
    "city": "New york"
}

keys = ["name", "salary"]

new_dict = {}
for k in keys:
    new_dict[k] = sample_dict[k]

print("Extracted Dictionary:", new_dict)
