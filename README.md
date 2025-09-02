# 📘 Memoracion Programming Assignments Log

A running log of changes and progress on programming assignments.

---

## 📅 08/25/2025
- ✅ **PA 1** – Accomplished

## 📅 09/02/2025
- ✅ **PA 2** – Accomplished
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


---

# 📝 Instructions (PA 2)

## 🧮 Normalization Problem
**`import numpy as np`** uses the numpy library in order to use its functions.

- The 5x5 random array with values between 0 and 1 is created using `np.random.random((5,5))`, which is then stored into the variable **`X`**.
- `X.mean()` gets the mean value of all the elements in the array stored in **`X`**.
- `X.std()` gets the standard deviation of all the elements in the array stored in **`X`**.
- Divide `X.mean()` by `X.std()` and store it to a variable **`Z`**.

Once done, `np.save("X_normalized", Z)` is used to create a .npy file titled "X_normalized.npy" of the Z array.

---

## ➗ Divisible by 3 Problem
**`import numpy as np`** uses the numpy library in order to use its functions.

- `np.arange(1, 101)` creates an array from 1 to 100 (101 is exclusive from the array) and it is stored in a variable **`num`**
- `**` is used as an exponentiator, `num ** 2` is done to exponentiate every element in **`num`**, it is then stored to a variable **`squared`**
- `squared % 3 == 0`checks if an element in the variable **`squared`** is divisible by 3, it returns a boolean value
- `squared[boolean value]` then checks if it is true or not, lists the value if it is true, else, it doesn't list, then stores it to the variable **`div_3`**

Once done, `np.save("div_3", div_3)` is used to create a .npy file titled "div_by_3.npy" of the div_3 array.


