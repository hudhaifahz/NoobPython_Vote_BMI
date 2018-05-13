height = float(input('Height (cm)?'))
H = (height)/100*(height)/100
weight = float(input ('Weight (kg)?'))
BMI = float(weight)/H
print("Your BMI is:",int(BMI))
if BMI<=18.5:
    print("You are Underweight")
if 18.5<BMI<=25:
    print("You are Normal")
if 25<BMI<=30:
    print("You are Overweight")
if BMI>30:
    print("You are Obese")
input()
