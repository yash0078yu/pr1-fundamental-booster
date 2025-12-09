# pr1-fundamental-booster

This program accepts user details such as name, age, height, and favourite number, then prints the values along with their data types and memory IDs. It also calculates the approximate birth year based on the age provided.

## 📌 Features

* Takes input from the user:

  * Name (string)
  * Age (integer)
  * Height in meters (float)
  * Favourite number (integer)
* Calculates birth year using: `2025 - age`
* Displays values, their data types, and memory IDs

🧾 Code
`python
name = input("Please enter your name: ")
age = int(input("Please enter your age: "))
height = float(input("Please enter your height in meters: "))
fav_number = int(input("Please enter your favourite number: "))

birth_year = 2025 - age  

print(name)
print(age)
print(height)
print(fav_number)

print(name, type(name), id(name))
print(age, type(age), id(age))
print(height, type(height), id(height))
print(fav_number, type(fav_number), id(fav_number))

print("Your birth year is approximately:", birth_year, "based on your age of", age)
```

## ▶️ How to Run

1. Copy the code into any Python (.py) file.
2. Run it in a terminal or Python IDE.
3. Enter the requested details when prompted.

## 📌 Output Example

* Shows the entered data
* Displays type and memory ID of each variable
* Shows calculated birth year

## ✔️ Requirements

* Python 3.x installed on your system
