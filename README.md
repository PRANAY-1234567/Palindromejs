🔁 Palindrome Checker in JavaScript

📌 Description

This program checks whether a given string is a Palindrome or not using JavaScript.

A palindrome is a word, phrase, or number that reads the same forward and backward.

🧩 Problem Statement

Given a string:

Check if the original string is equal to its reversed version.

Example

Input: "madam"
Output: true

✅ Code
function isPalindrome(str) {
  return str === str.split("").reverse().join("");
}

console.log(isPalindrome("madam"));

🧠 Explanation

The function isPalindrome() takes a string as input

The string is reversed using split(), reverse(), and join()

The original string is compared with the reversed string

If both are the same → the string is a palindrome

🖨 Example Output
true

🛠 Concepts Used

JavaScript Functions

String comparison

Array methods (split, reverse, join)

Console output

🎯 Use Cases

Interview preparation

String logic problems

Beginner JavaScript practice

Text validation

🚀 Possible Improvements

Ignore case sensitivity

Remove spaces and special characters

Check numeric palindromes

Take user input

👨‍💻 Author
Pranay Jadhao

<img width="660" height="706" alt="image" src="https://github.com/user-attachments/assets/7af8b27b-d624-42d7-916b-572de957dd8b" />
