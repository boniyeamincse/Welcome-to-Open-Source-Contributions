# Challenge 03: Valid Parentheses

**Difficulty:** 🟡 Intermediate  
**Topics:** Stack, String Manipulation, Data Structures

## 📖 Description

Determine if a string of parentheses, brackets, and braces is valid.

## 🎯 Objectives

- Check if brackets are correctly matched and nested
- Use stack data structure
- Return true if valid, false otherwise

## 📋 Requirements

1. Valid characters: `()`, `[]`, `{}`
2. Must close in correct order
3. Every opening bracket must have a corresponding closing bracket
4. Include comprehensive test cases

## 💡 Example

```cpp
bool isValid(string s) {
    // Your code here
}

// Test cases
isValid("()")        // true
isValid("()[]{}")    // true
isValid("(]")        // false
isValid("([)]")      // false
isValid("{[]}")      // true
```

## 🌟 Bonus Points

- Provide helpful error messages
- Show which bracket is unmatched
- Handle edge cases (empty string, odd length)

## 📚 Learning Outcomes

- Understand stack data structure
- Practice string processing
- Learn pattern matching
- Common interview problem!
