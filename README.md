# Travel-Budget-Estimator
# Travel Budget Estimator

print("🚗 Welcome to the Travel Budget Estimator!")

# Get user input
distance = float(input("Enter the total distance of your trip (in miles): "))
miles_per_gallon = float(input("Enter your car's fuel efficiency (miles per gallon): "))
gas_price = float(input("Enter the current gas price per gallon: $"))

# Calculate total cost
gallons_needed = distance / miles_per_gallon
total_cost = gallons_needed * gas_price

# Display the result
print("\n--- Trip Summary ---")
print("Distance:", distance, "miles")
print("Fuel efficiency:", miles_per_gallon, "mpg")
print("Gallons needed:", round(gallons_needed, 2))
print("Estimated total fuel cost: $", round(total_cost, 2))

# Final message
print("\nHave a safe and budget-friendly trip! 🧳")
