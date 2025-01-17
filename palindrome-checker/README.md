<h1>
  <span class="headline">Linked Lists in Java Lab</span>
  <span class="subhead">Palindrome Checker</span>
</h1>

## Objective
Implement a **Palindrome Checker** that checks if the elements of a linked list form a palindrome.

## Requirements
- Implement a `PalindromeChecker` class using Java's `LinkedList` class. A linked list is a palindrome if the sequence of its elements reads the same forward and backward.
- Write a method, `isPalindrome()`, that:
   - Returns `true` if the linked list is a palindrome.
   - Returns `false` otherwise.
   - Solves the problem with a time complexity of O(n).
- Use the `PalindromeChecker` class in the starter code.
- The starter code includes a set of tests to help you verify your work. To run the tests, right-click on the `PalindromeCheckerTest` class in the `src/test/java` directory and select **Run 'All Tests'**.

### Example inputs and expected outputs
   **Input:**  
   List: `[r, a, d, a, r]`  
   **Output:**  
   `true`

   **Input:**  
   List: `[h, e, l, l, o]`  
   **Output:**  
   `false`

## Practical relevance
Reflecting on this exercise will help you understand how significant choosing the right data structure for a specific algorithm is. The doubly linked list which allows both forward and backward navigation without any extra code, makes a palindrome checker algorithm very simple. The right data structure will lend itself intuitively and naturally to make an algorithm simple and efficient.
