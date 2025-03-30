# Powerlearnproject-week-python-assignment
Week 3 assignment 
def calculate_discount(price, discount_percent):
    """Calculates the final price after applying a discount if it is 20% or higher."""
    if discount_percent >= 20:
        discount_amount = (discount_percent / 100) * price
        return price - discount_amount
    return price

# Prompt the user for input
price = float(input("Enter the original price of the item: "))
discount_percent = float(input("Enter the discount percentage: "))

# Calculate and display the final price
final_price = calculate_discount(price, discount_percent)
print(f"Final price after discount (if applied): {final_price:.2f}")

