Here’s a clean and beginner-friendly **README.md** for your Python program that **prints characters in reverse**:

---

# 🔁 Print Characters in Reverse – Python Program

This simple Python program takes a string input from the user and prints each character **in reverse order**, one character per line. It's a great practice task for string handling and loop concepts.

## 📌 Description

* The user is prompted to enter a string.
* The program calculates the length of the string.
* It uses a `for` loop to iterate from the end of the string to the beginning.
* Each character is printed on a new line in reverse order.

### 🧾 Sample Input & Output

**Input:**

```
hello
```

**Output:**

```
o  
l  
l  
e  
h  
```

## 🧠 Logic

* Use `len()` to get the length of the input string.
* Loop from `1` to `length + 1`.
* In each iteration, access and print the character from the end using index `length - i`.

## 🧾 Code

```python
a = input("Enter a string: ")
length = len(a)
for i in range(1, length + 1):
    print(a[length - i])
```

## 🛠️ How to Run

1. Save the code in a file, for example: `reverse_chars.py`
2. Run it using Python:

```bash
python reverse_chars.py
```

3. Enter any string to see its characters printed in reverse.

## 🎯 Use Case

* Useful for learning:

  * String indexing
  * Loops and iteration
  * Working with user input

* Can be extended to:

  * Print the reversed string on a single line
  * Skip spaces or special characters
  * Check for palindromes

## 📬 Contact  

For any inquiries or feedback, feel free to reach out:    
🔗 **GitHub**: [Rachana-Hegde](https://github.com/Rachana-Hegde)  


