# NBMI
print("How to calculate BMI?")
h=int(input("Enter Height in Meters:"))
height=h*0.01
print("Height",height)
w=int(input("Enter weight in kg:"))
he=height*height
bmi=w/he
print(bmi)

if bmi >=18.5 and bmi <=24.9:
    print("----------------------------------------------------")
    print("BMI                      ||           CLASSIFICATION")
    print(bmi,"                        Normal")

elif bmi <= 18.5:
    print("----------------------------------------------------")
    print("BMI                      ||           CLASSIFICATION")
    print(bmi, "                  Underweight")

elif bmi >=25 and bmi <=29.9:
    print("----------------------------------------------------")
    print("BMI                      ||           CLASSIFICATION")
    print(bmi, "                   Overweight")

elif bmi >= 30 and bmi <= 34.9:
    print("----------------------------------------------------")
    print("BMI                      ||           CLASSIFICATION")
    print(bmi, "                   Obesity class |")

elif bmi >= 35 and bmi <= 39.9:
    print("----------------------------------------------------")
    print("BMI                      ||           CLASSIFICATION")
    print(bmi, "                   Obesity class ||")

else:
    print("----------------------------------------------------")
    print("BMI                      ||           CLASSIFICATION")
    print(bmi, "                   Extreme Obesity")
