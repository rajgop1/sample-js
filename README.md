# LocalStorage Array Practise

## Features
- Store and retrieve an array in `localStorage`
- Add new items to the array
- Remove specific items from the array
- Clear all stored data

## Template Code

```javascript
// Initialize the array from localStorage or set it as an empty array
let dataArray = JSON.parse(localStorage.getItem("myArray")) || [];

/**
 * Adds an item to the array and updates localStorage.
 * @param {string} item - The item to be added.
 */
function addItem(item) {
    // TODO: Implement adding item logic
}

/**
 * Retrieves the stored array from localStorage.
 * @returns {Array} The stored array.
 */
function getItems() {
    // TODO: Implement retrieval logic
}

/**
 * Removes an item at a given index and updates localStorage.
 * @param {number} index - The index of the item to remove.
 */
function removeItem(index) {
    // TODO: Implement item removal logic
}

/**
 * Clears all data from the array and removes it from localStorage.
 */
function clearData() {
    // TODO: Implement clearing logic
}

// Example usage (Remove comments when implementing)
// console.log("Initial Data:", getItems());
// addItem("Example Item");
// console.log("After Adding Item:", getItems());
// removeItem(0);
// console.log("After Removing Item:", getItems());
// clearData();
// console.log("After Clearing Data:", getItems());
```

## How to Use
1. Implement the logic inside the functions.
2. Use `addItem()` to add new items.
3. Use `getItems()` to retrieve the array.
4. Use `removeItem(index)` to delete a specific item.
5. Use `clearData()` to reset the array.

Modify the script as needed to fit your project! 🚀
