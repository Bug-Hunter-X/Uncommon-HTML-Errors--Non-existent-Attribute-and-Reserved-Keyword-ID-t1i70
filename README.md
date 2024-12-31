# Uncommon HTML Errors

This repository demonstrates a couple of uncommon errors that can occur in HTML:

1. **Attempting to access a non-existent attribute:**  This leads to a `TypeError` because you're trying to read a property from an object (in this case, a DOM element) that doesn't exist.  This is often caused by typos or misunderstandings of the DOM structure.
2. **Using a reserved keyword as an ID:** HTML IDs should not use reserved keywords of the language (like `for`, `class`, etc.).  This can cause unexpected behavior or parsing errors.

The `bug.html` file contains the erroneous code.  `bugSolution.html` shows corrected versions.