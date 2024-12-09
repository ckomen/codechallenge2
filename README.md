CK's Interactive Shopping List
This project is a dynamic, interactive shopping list application that allows users to manage a shopping list with item names and prices. Users can add new items, mark items as purchased, delete individual items, and clear the entire list. The application uses local storage to ensure data persistence across page reloads.

Features
Add Items: Add items with names and prices to the shopping list.
Mark as Purchased: Toggle the purchased status of any item in the list.
Delete Items: Remove individual items from the list.
Clear List: Clear all items from the shopping list with a single click.
Persistent Storage: Automatically saves and retrieves the shopping list using local storage.
Responsive UI: Provides a clean and responsive design for ease of use.
Technology Stack
HTML: Provides the structure of the web application.
CSS: Styles the application for a visually appealing and responsive user experience.
JavaScript: Adds interactivity and handles dynamic operations like adding, deleting, and persisting data.
Setup and Usage
1. Prerequisites
Ensure you have a modern web browser (e.g., Google Chrome, Mozilla Firefox) installed on your system.

2. Installation
Clone or download this repository to your local machine.
Extract the files to your desired directory.
3. Running the Application
Open the index.html file in your web browser.
Use the provided input fields and buttons to interact with the shopping list.
File Structure
The project includes the following files:

HTML (index.html):

Contains the structure of the shopping list application.
Includes input fields, buttons, and a container for displaying the list.
CSS (styles.css):

Styles the shopping list application.
Adds responsiveness, hover effects, and a clean layout.
JavaScript (script.js):

Implements all the functionality, such as adding, deleting, and marking items as purchased.
Handles data persistence using local storage.
How It Works
1. Adding Items
Enter an item name and price in the input fields.
Click the "Add Item" button.
The item appears in the list and is stored in local storage.
2. Marking Items as Purchased
Click an item to toggle its purchased status.
Purchased items are visually updated with a green background and strikethrough text.
3. Deleting Items
Click the "Delete" button next to an item to remove it from the list and local storage.
4. Clearing the List
Click the "Clear List" button to remove all items from the list and clear local storage.
Enhancements
Potential future improvements include:

Allow editing of item names and prices directly in the list.
Add sorting functionality (e.g., by name or price).
Display the total cost of all items in the list.