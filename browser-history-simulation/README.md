<h1>
  <span class="headline">Linked Lists in Java Lab</span>
  <span class="subhead">Browser History Simulation</span>
</h1>

## Objective
Simulate a browser history management system using Java's `LinkedList` class.

## Requirements
- Implement a `BrowserHistory` class that supports the following operations:
  1. **Open a New Page:** Open a new page in the browser and add it to the end of the history.
  2. **Move to the Next Page in History:** Navigate forward to the next page in history (if it exists).
  3. **Move to the Previous Page in History:** Navigate backward to the previous page in history (if it exists).
  4. **Display Browser History:** Display all pages in the order in which they were opened.
- Manage browser history in a way that users can navigate back and forth between pages.
- Assume the current position in history when navigating forward or backward.
- Use the `BrowserHistory` class in the starter code.
- The starter code includes a set of tests to help you verify your work. To run the tests, right-click on the `BrowserHistoryTest` class in the `src/test/java` directory and select **Run 'All Tests'**.

### Example inputs and expected outputs
1. **Example 1:**  
   - Operations: Open pages: `"Home"`, `"About"`, `"Contact"`  
   - Output: History: `[Home, About, Contact]`
   - Current Page: `"Contact"`

2. **Example 2:**  
   - Operations: Open `"Home"`, move to the next page (no effect), move back,  
     open `"New Page"` after navigating backward.  
   - Output: History: `[Home, New Page]`

## Practical relevance
- This exercise will help you understand how utilitarian doubly linked lists are and how we use them in our applications that we use everyday. As a developer, a good command on working with doubly linked lists will help code for operations that depend on preservation of sequence history such as navigation, undo-redo, etc.

