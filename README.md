# 📘 Memoracion Programming Assignments Log

A running log of changes and progress on programming assignments.

---

## 📅 08/25/2025
- ✅ **PA 1** – Accomplished

---

# 📝 Instructions (PA 1)

## 📌 Alphabet Soup Problem
The **`alphabet_soup`** function takes a word as input and returns the letters of the word sorted in alphabetical order.

- If the input is invalid (too short or contains non-alphabetic characters), the program will display the error message:  
  `"You did not put a valid word"`  
  and ask the user to enter another word.
- Once a valid word is provided:
  - The function sorts the letters alphabetically using **`sorted()`** with **`key=str.lower`** (case-insensitive sorting).
  - The **`"".join()`** function combines the sorted letters into a single string without spaces.
- Finally, it prints the arranged string.

---

## 😊 Emoticon Problem
The **`emotify`** function takes a sentence as input and replaces certain words with their corresponding emoticons.

- It uses a dictionary (**`emojis`**) to map words to emoticons:
  - `"smile"` → 🙂
  - `"grin"` → 😁
  - `"sad"` → 😢
  - `"mad"` → 😠
- The sentence is:
  - Split into words using **`.split()`**.
  - Each word is checked (case-insensitive with **`.lower()`**) against the dictionary.
  - If the word exists, it is replaced with its emoticon; otherwise, it remains unchanged.
- Finall








      
