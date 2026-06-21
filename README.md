# Expense-Tracker-Project-2

# Simple Expense Tracker

total = 0

print("Expense Tracker")
print("Enter your expenses one by one.")
print("Type 0 to finish.\n")

while True:
    expense = float(input("Enter expense amount: "))

    if expense == 0:
        break

    total = total + expense

print("\nTotal Spent: ₹", total)
