# 🛒 CK's Interactive Shopping List

Welcome to **CK's Interactive Shopping List**! This is a dynamic and interactive web application that allows users to easily manage their shopping list. With this app, you can:

- Add items with names and prices.
- Mark items as purchased (with visual changes like strikethrough and color).
- Delete individual items.
- Clear the entire list in one click.

The list data is stored in **localStorage**, ensuring the list remains intact even after closing or refreshing the browser.

---

📂 File Structure

HTML (index.html): Defines the structure of the webpage.
Input fields for item name and price.
Buttons to add items, clear the list, and interact with individual items.
An unordered list (<ul>) to display shopping list items dynamically.

CSS (styles.css): Applies styling to enhance the app's appearance.
Responsive design that adjusts the layout based on screen size.
Visual differentiation between purchased and unpurchased items.
Hover effects for buttons and interactive elements.

JavaScript (script.js): Implements the functionality of the shopping list.
Adds, deletes, and toggles items.
Saves the list to and retrieves it from localStorage.
Dynamically renders the list items on page load.

🔑 Key Functions

1. Render List:
Clears and re-renders the shopping list.
Applies visual styles to items based on their purchased status.
2. Update Local Storage:
Saves the shopping list to localStorage so that it persists across sessions and page reloads.
3. Event Listeners:
Handles button clicks for adding, clearing, and deleting items.
Allows toggling of the purchased state by clicking on a list item.
🚀 How It Works
1. Adding Items:
Enter an item name and price in the input fields.
Click the "Add Item" button to add the item to the list.
The item will be added to the list and stored in localStorage for persistence.
2. Marking Items as Purchased:
Click on a list item to toggle its purchased status.
Purchased items will be visually updated with a green background and strikethrough text.
3. Deleting Items:
Click the "Delete" button next to an item to remove it from the list.
The item will be deleted from both the UI and localStorage.
4. Clearing the List:
Click the "Clear List" button to remove all items.
The list will be cleared from both the UI and localStorage.

✨ Enhancements

Editable Items: Allow users to edit the item names and prices directly in the list.
Sorting: Add options to sort items by name or price.
Total Price Display: Show the total price of all items in the list for a quick overview.
