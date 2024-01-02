# Guided Assignment - Introduction to `Console.WriteLine()` and `Console.Write()` in C#


## Introduction to Console.WriteLine() and Console.Write()

In C#, `Console.WriteLine()` and `Console.Write()` are used for outputting text to the console. They are similar but have a key difference:

- `Console.WriteLine()`: Outputs the text and moves the cursor to the next line.
- `Console.Write()`: Outputs the text but keeps the cursor on the same line.

We'll explore how to use these methods effectively.

---

## Requirements

1. Create a new console application called GA_WriteLine_***YourName***

2. Using the new skills you learn here print the following text in your console. It should be formatted exactly the same way.

The names should use a `Console.Write()` and the quotes should be in a `Console.WriteLine()`.



```
1. Edsger W. Dijkstra: Computer science is no more about computers than astronomy is about telescopes.

2. Alan Kay: The best way to predict the future is to invent it.

3. Grace Hopper: The most damaging phrase in the language is, We’ve always done it this way.

4. Terry Pratchett (Discworld): It's not worth doing something unless someone, somewhere, would much rather you weren't doing it.
```

3. Upload your assignment on github and submit the repository link to canvas.


---

## Step By Step

### Step 1: Using Console.WriteLine()

`Console.WriteLine()` is commonly used to display messages or output. It automatically adds a newline at the end of the output.

1. Add the following code inside the Main method:

    ```csharp
    Console.WriteLine("Hello, World");
    ```

2. Run your code.
   - You'll see "Hello, World" printed, and the cursor moves to the next line.

   ```
   Hello, World!
   ```

---

### Step 2: Exploring Console.Write()

Now let's see how `Console.Write()` works.

1. Replace `Console.WriteLine()` with `Console.Write()`:

    ```csharp
    Console.Write("Hello, World");
    ```

2. Add another `Console.Write()` after it:

    ```csharp
    Console.Write("Hello, World");
    Console.Write(" This is on the same line.");
    ```

3. Run your code.
   - Notice both texts appear on the same line.

   ```
   Hello, World! This is on the same line.
   ```

---

### Step 3: Mixing Console.WriteLine() and Console.Write()

We can mix these methods for varied formatting.

1. Add `Console.WriteLine()` after `Console.Write()`:

    ```csharp
    Console.Write("Hello, World");
    Console.WriteLine(" This is on the same line.");
    Console.WriteLine("Now, this is on a new line.");
    ```

2. Run your code.
   - The first two strings appear on the same line, and the third string starts on a new line.

  ```
   Hello, World! This is on the same line.
   Now, this is on a new line.
   ```


---

## Rubric

| Criteria | Points | Description |
|----------|--------|-------------|
| **Project Setup** | 20 | Creation of a new console application named correctly as GA_WriteLine_YourName. Proper organization of files and folders. |
| **Code Correctness** | 30 | Correct usage of `Console.Write()` for author names and `Console.WriteLine()` for quotes. |
| **Output Accuracy** | 30 | Output in the console matches the provided text exactly, including punctuation, capitalization, and spacing. |
| **Code Readability and Comments** | 10 | Clear and readable code with adequate comments explaining the code. |
| **Submission** | 10 | Code successfully pushed to GitHub and correct submission on Canvas. |
| **Total** | 100 |  |

"""

---

### Conclusion

`Console.WriteLine()` and `Console.Write()` are essential for displaying output in C#. `Console.WriteLine()` is more common for line-by-line outputs, while `Console.Write()` gives more control over text placement. By practicing with these methods, you can create interactive and user-friendly console applications.

Feel free to experiment by combining different texts and these methods to see how the output changes!

---

OpenAI's ChatGPT. "Guided Assignment - Introduction to Console.WriteLine() and Console.Write() in C#." OpenAI, 2 Jan. 2024, [URL of ChatGPT or platform used].