#Write a program that asks your name and age, then prints what year you’ll turn 50.
name=input("enter your name:")
age=input("enter your age:")
current_year=2025
a=50-int(age)
afteryear=current_year+a
print("Hello",name, "your will be 50 at the year ",afteryear)