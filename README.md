def calculate_budget(income, expenses):
    total_income = sum(income)
    total_expenses = sum(expenses)
    budget = total_income - total_expenses
    return budget

# Example usage
income = [1000, 2000, 1500]  # List of your income sources
expenses = [500, 800, 600]  # List of your expenses

# Calculate the budget
my_budget = calculate_budget(income, expenses)

# Print the result
print(f"My budget: {my_budget}")
