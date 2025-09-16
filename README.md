# Welcome message for the tip calculator
print("Welcome to tip calculator!")
#Input for bill and converting the data to integer
bill = int(input("What was your total bill? "))
#Input for tip and converting the data to integer
tip = int(input("How much percentage tip would you like to give? 10, 12, or 15 "))
#Input for number of people sharing the bill and converting it to integer
no_of_people = int(input("How many people are splitting the bill? "))
# Calculating the total amount to pay including the percentage of the tip
bill_to_pay_tip  =(bill+ tip/100* bill )
# Calculating the  amount of bill per person
bill_per_person = round(bill_to_pay_tip/no_of_people,2)

print(f"Your are to pay:  ${bill_per_person} ")
