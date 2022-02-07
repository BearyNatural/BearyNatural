#greeting
print("Welcome to the tip calculator.\n")

#user input for bill total
total_bill = input("What was the total Bill?\n $")

#percentage of tip given
percentage_tip = input("What percentage tip would you like to give?\n")

#Bill split value
split_bill = input("How many people to split the bill?\n")

#change all data from string to integer
tb = float(total_bill)
pt = int(percentage_tip)
sb = int(split_bill)

#calculation
equal_share = '{:.2f}'.format(round(((tb*(pt/100)+tb)/sb), 2))

#print each persons share
print("Each person should pay: $", equal_share)
