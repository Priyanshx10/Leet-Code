# Longest Substring Without Repeating Characters (LeetCode #3)

## 📄 Problem Statement

Given a string `s`, find the length of the **longest substring** without duplicate characters.

A **substring** is a contiguous sequence of characters within a string (not to be confused with a subsequence).

---

## 📝 Examples

### Example 1

**Input:**  
`s = "abcabcbb"`

**Output:**  
`3`

**Explanation:**  
The answer is `"abc"`, with the length of `3`.

---

### Example 2

**Input:**  
`s = "bbbbb"`

**Output:**  
`1`

**Explanation:**  
The answer is `"b"`, with the length of `1`.

---

### Example 3

**Input:**  
`s = "pwwkew"`

**Output:**  
`3`

**Explanation:**  
The answer is `"wke"`, with the length of `3`.  
Notice that the answer must be a substring, `"pwke"` is a subsequence and not a substring.

---

## 🔒 Constraints

- `0 <= s.length <= 5 * 10^4`
- `s` consists of **English letters, digits, symbols, and spaces**.

---

## 💡 Follow-up

Can you solve this in **O(n)** time complexity using the **sliding window technique**?
