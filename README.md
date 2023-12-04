# Problem-5
total = 0
tax = 0.07

def compute_total_and_tax(quantity, unit_price):
    global total
    total = quantity * unit_price
    tax_amount = total * tax
    return total, tax_amount

quantity = float(input("Enter quantity of the item: "))
unit_price = float(input("Enter unit price: "))

total_amount, tax_amount = compute_total_and_tax(quantity, unit_price)

print(f"Total: {total_amount}")
print(f"Tax: {tax_amount}")
