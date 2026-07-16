# Palindrome Checker in JavaScript

## 📌 Overview

This project demonstrates how to check whether a given string is a **palindrome** using JavaScript.
A palindrome is a word, phrase, or sequence that reads the same forward and backward. The program reverses the input string using built-in string and array methods, then compares it with the original string to determine whether it is a palindrome.

This is a simple and beginner-friendly project for learning string manipulation and JavaScript functions.

---

## 🚀 Features

* Checks whether a string is a palindrome
* Uses built-in JavaScript methods (`split()`, `reverse()`, `join()`)
* Returns `true` for palindromes and `false` otherwise
* Simple, reusable function
* Displays the result in the console

---

## 🛠️ Technologies Used

* JavaScript (ES6+)

---

## 📂 Project Structure

```text
├── palindromeChecker.js
└── README.md
```

---

## 💻 Source Code

```javascript
function isPalindrome(str) {
    return str === str.split("").reverse().join("");
}

console.log(isPalindrome("madam"));
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/javascript-palindrome-checker.git
cd javascript-palindrome-checker
```

### Run Using Node.js

```bash
node palindromeChecker.js
```

Or paste the code into your browser's Developer Console and execute it.

---

## 📋 Sample Output

### Example 1

```text
Input : "madam"
Output: true
```

### Example 2

```text
Input : "racecar"
Output: true
```

### Example 3

```text
Input : "hello"
Output: false
```

---

## 🧠 Concepts Covered

* JavaScript Functions
* String Manipulation
* Arrays
* `split()` Method
* `reverse()` Method
* `join()` Method
* Boolean Values
* Console Output

---

## 🔍 How It Works

1. Accept a string as input.
2. Convert the string into an array using `split("")`.
3. Reverse the array using `reverse()`.
4. Join the array back into a string using `join("")`.
5. Compare the reversed string with the original string.
6. Return `true` if they are equal; otherwise, return `false`.

---

## ⏱️ Complexity Analysis

| Operation        | Complexity |
| ---------------- | ---------- |
| Time Complexity  | **O(n)**   |
| Space Complexity | **O(n)**   |

Where **n** is the length of the input string.

---

## 🔮 Future Improvements

* Ignore uppercase and lowercase differences
* Ignore spaces and punctuation
* Accept user input dynamically
* Check numeric palindromes
* Build a simple web interface with HTML and CSS

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

* How to manipulate strings in JavaScript
* How to use `split()`, `reverse()`, and `join()`
* How to write reusable functions
* How to compare strings and return Boolean values

---

## 👨‍💻 Author

**Pranay Jadhao**

Electronics & Telecommunication Engineer

Aspiring Software Engineer | JavaScript | Python | Java | SQL

---

## 📄 License

This project is open-source and available for educational and learning purposes.


<img width="660" height="706" alt="image" src="https://github.com/user-attachments/assets/7af8b27b-d624-42d7-916b-572de957dd8b" />
