# Python Task 1: Haiku Libs

**Objective:** Create a simple Haiku-style poem to input different words to generate a Haiku.

**Instructions:**
1. **Print a welcome message:** Use the `print` function to display a welcome message.
2. **Get user input:** Use the `input` function to ask the user for different types of words (name, animal, place).
3. **Combine strings and variables:** Use the `+` operator to combine strings and variables in the print statements.
4. **Use comments:** Add comments to explain each section of the code.

**Example Code:**

```python
# Print a welcome message
print("Welcome to Haiku Libs - Answer the following questions to create your haiku")

# Get user inputs
name = input("Enter a name:")  # User inputs a name
animal = input("Enter an animal (singular):")  # User inputs an animal (singular)
place = input("Enter a place:")  # User inputs a place

# Print the completed haiku
print("--------HAIKU START--------")
print(name + " sees a " + animal)  # Combine and print name and animal
print("In the quiet of " + place)  # Combine and print place
print("Peaceful and serene")  # Print the last line of the haiku
print("--------HAIKU END--------")
```

**Expected Output:**

```
Welcome to Haiku Libs - Answer the following questions to create your haiku
Enter a name: [Student inputs "Alice"]
Enter an animal (singular): [Student inputs "cat"]
Enter a place: [Student inputs "garden"]

--------HAIKU START--------
Alice sees a cat
In the quiet of garden
Peaceful and serene
--------HAIKU END--------
```