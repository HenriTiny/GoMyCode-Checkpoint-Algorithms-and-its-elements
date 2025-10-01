# Algorithm `read_sentence`

## Description

This algorithm reads a sentence, character by character, until it encounters a period (`.`), and determines:

- The **length** of the sentence (total number of characters)
- The **number of words** (assuming they are separated by a single space).
- The **number of vowels** (`a, e, i, o, u` in lower and upper case).

---

## Functioning

The user enters a sentence that must end with a period (`.`).
The algorithm scans each character before this period and performs the following processing:

- **Count vowels** by comparing each character to a list of vowels.
- **Count words** with each detected space.
- **Count character**.

---

## File

**File name :** `read_sentence.algo`
**Language:** Algo/Structogram (academic pseudo-code)

---

## Exemple

User input :
Hello world.
Output :
Length of the sentence : 11
Number of vowels : 3
Number of words : 2

## Variable details

| Variable           | Type    | Description                                 |
| ------------------ | ------- | ------------------------------------------- |
| `sentence`         | STRING  | User-entered sentence                       |
| `vowels_list`      | STRING  | List of vowels to test                      |
| `i, j`             | INTEGER | Loop index                                  |
| `count_characters` | INTEGER | Number of characters in the sentence        |
| `count_words`      | INTEGER | Number of words                             |
| `count_vowels`     | INTEGER | Number of vowels                            |
