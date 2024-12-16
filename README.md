# Urvi
print("Welcome to the Interactive Personal Data Collector!\n")

name = input("Please enter your name: ")
age = int(input("Please enter your age: "))
height = float(input("Please enter your height in meters: "))
fav_no = int(input("Please enter your favourite number: "))

print("\nThank you! Here is the information we collected:\n")

print("Name:" , name , "(Type:" , type(name) , ", Memory Address:" , id(name) , ")")
print("Age:" , age , "(Type:" , type(age) , ", Memory Address:" , id(age) , ")")
print("Height:" , height , "(Type:" , type(height) , ", Memory Address:" , id(height) , ")")
print("Favourite Number:" , fav_no , "(Type:" , type(fav_no) , ", Memory Address:" , id(fav_no) , ")\n")

from datetime import date

curent_date = date.today()

curent_year = curent_date.year

birth_year = curent_year - age
print("Your birth year is approximately:" , birth_year , "(based on your age of" , age ,")\n")
print("Thank you for using the Personal Data Collector. Goodbye!")
