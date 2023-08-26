---
name: User Story
about: Creating user stories.
title: ''
labels: ''
assignees: ''

---

**As a** [role]  
 **I need** [function]  
 **So that** [benefit]  
   
 ### Details and Assumptions
 * [document what you know]
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given [some context]
 When [certain action is taken]
 Then [the outcome of action is observed]
 ```


# Create an empty list to store the grocery items
grocery_list = []

# Function to add items to the list
def add_item(item):
    grocery_list.append(item)
    print(f"{item} added to the list.")

# Function to display the list
def display_list():
    print("Grocery List:")
    for item in grocery_list:
        print(f"- {item}")

# Add items to the list
add_item("Apples")
add_item("Milk")
add_item("Bread")
add_item("Eggs")

# Display the list
display_list()