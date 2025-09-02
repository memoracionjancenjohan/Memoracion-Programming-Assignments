# 📘 Memoracion - Programming Assignment 1

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
  - `"smile"` → :)
  - `"grin"` → :D
  - `"sad"` → :((
  - `"mad"` → >:(
- The sentence is:
  - Split into words using **`.split()`**.
  - Each word is checked (case-insensitive with **`.lower()`**) against the dictionary.
  - If the word exists, it is replaced with its emoticon; otherwise, it remains unchanged.
- Finally, the words are joined back into a sentence with **`" ".join()`** and returned.
- The program then prints the new sentence.

---

## 📦 Unpacking List Problem
The **`unpack_list`** function takes a list as input and splits it into three parts:

- **First**: gets the first element → **`lst[0]`**
- **Middle**: gets all elements except the first and last → **`lst[1:-1]`**
- **Last**: gets the last element → **`lst[-1]`**

The function returns these three variables together as a tuple using **`return`**, and then prints them from the input.
