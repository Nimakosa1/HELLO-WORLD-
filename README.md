print("FRED CHILLS")
print()
message="welcome to the restaurant bill calculator"
print(message.upper())
print("-" * len(message))
print() 
 
amount=float(input("Amount spent on food:" ))
partySize=float(input("Number of people splitting bill:" ))
name="Fred Chills"
#assuming Tip is 25 Percent
tipP=25/100
tip=tipP * amount
total=amount + tip
perPerson=total/partySize
print()
print("Your bill for", name.upper(),"--\n") 
print("Subtotal: GHC", format(amount, '.2f'))
print("Tip: GHC", format(tip, '.2f'))
print("Total: GHC", format(total, '.2f'))
print("Amount per Person: GHC", format(perPerson, '.2f'))
print()
print("Thank you for your Patronage!" )
print()
print()
print()
txt=("A L F R E D'S   C H I L L S ©" )
x=txt.center(43)
print(x)

