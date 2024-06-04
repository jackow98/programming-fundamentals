# Python Task 2: Rap Libs

**Objective:** Create a simple Madlibs-style game to input different types of words to generate a fun rap-style paragraph.

**Instructions:**
1. **Print a welcome message:** Use the `print` function to display a welcome message.
2. **Get user input:** Use the `input` function to ask the user for different types of words (name, school subject, animal, location, celebrity, singer).
3. **Combine strings and variables:** Use the `+` operator to combine strings and variables in the print statements.
4. **Use comments:** Add comments to explain each section of the code.

**Example Code:**

```python
# Print a welcome message
print("Welcome to Rap Libs - Answer the following questions to create your rap libs")

# Get user inputs
name = input("Enter a name:")  # User inputs a name
school_subject = input("Enter a school subject:")  # User inputs a school subject
animal = input("Enter an animal (singular):")  # User inputs an animal (singular)
location = input("Enter a city/country:")  # User inputs a city or country
celebrity = input("Enter a celebrity:")  # User inputs a celebrity
singer = input("Enter a singer:")  # User inputs a singer

# Print the completed rap lib
print("--------RAPLIBS START--------")
print("Y'all know me by now, " + name)  # Combine and print name
print("I'm the biggest rapper in the game, ")
print("The " + school_subject + " god")  # Combine and print school subject
print("King of " + location)  # Combine and print location
print("Rapping bout " + animal + "s till I die")  # Combine and print animal
print("And at the end of the day, you know I can bring it like " + celebrity)  # Combine and print celebrity
print("Droppin' classics harder than " + singer)  # Combine and print singer
print("--------RAPLIBS END--------")
```

**Expected Output:**

```
Welcome to Rap Libs - Answer the following questions to create your rap libs
Enter a name: [Student inputs "John"]
Enter a school subject: [Student inputs "Maths"]
Enter an animal (singular): [Student inputs "dog"]
Enter a city/country: [Student inputs "Scotland"]
Enter a celebrity: [Student inputs "Beyonce"]
Enter a singer: [Student inputs "Adele"]

--------RAPLIBS START--------
Y'all know me by now, John
I'm the biggest rapper in the game,
The Maths god
King of Scotland
Rapping bout dogs till I die
And at the end of the day, you know I can bring it like Beyonce
Droppin' classics harder than Adele
--------RAPLIBS END--------
```