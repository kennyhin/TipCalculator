# TipCalculator
print("Welcome to the tip calculator!")
bill = input ("What was the total bill?$")
tip = input ("How much tip would you like to give? 10,12,or 15?")
ppl_split = input("How many people to split the bill?")

bill_float = float(bill)
tip_float = float(tip)
ppl_split_float = float(ppl_split)

result = (bill_float/ppl_split_float)*(1+(tip_float/100))

new_result = round(result,2)
print(f"Each person should pay: ${new_result}")
