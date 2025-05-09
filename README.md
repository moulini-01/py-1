# py-1
temperature converter
temp=int(input("enter temperature: "))
units=int(input("enter units: "))
units_to_fahrenheit=units*(9/5)+32
units_to_kelvin=273+units
print(f"temp in fahrenheit:{units_to_fahrenheit}F")
print(f"temp in kelvin:{units_to_kelvin}K")
