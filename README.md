# Java, Python, and JavaScript: `for` Loop Comparison

Learn how the `for` loop works in Java, Python, and JavaScript by comparing their syntax, behavior, and key differences.

---

# Overview

Loops are one of the most fundamental programming concepts. They allow developers to execute a block of code repeatedly based on a specific condition.

This guide compares the implementation of the `for` loop in three popular programming languages: Java, Python, and JavaScript.

---

# ☕ 1. Java – `for` Loop

```java
public class LoopExample {
    public static void main(String[] args) {

        // Loop from 0 to 4 (5 iterations)
        for (int i = 0; i < 5; i++) {
            System.out.println("Java loop iteration: " + i);
        }

    }
}
```

## Explanation

- `int i = 0` → Initializes the loop counter at **0**.
- `i < 5` → Continues looping while `i` is less than **5**.
- `i++` → Increments `i` by **1** after each iteration.

### Output

```
Java loop iteration: 0
Java loop iteration: 1
Java loop iteration: 2
Java loop iteration: 3
Java loop iteration: 4
```

---

# 🐍 2. Python – `for` Loop

```python
# Loop from 0 to 4 (5 iterations)

for i in range(5):
    print(f"Python loop iteration: {i}")
```

## Explanation

- `range(5)` generates the sequence **0, 1, 2, 3, 4**.
- The variable `i` automatically receives each value from the sequence.
- Python automatically handles iteration, so there is no need for `i++`.

### Output

```
Python loop iteration: 0
Python loop iteration: 1
Python loop iteration: 2
Python loop iteration: 3
Python loop iteration: 4
```

---

# 🌐 3. JavaScript – `for` Loop

```javascript
// Loop from 0 to 4 (5 iterations)

for (let i = 0; i < 5; i++) {
    console.log(`JavaScript loop iteration: ${i}`);
}
```

## Explanation

- `let i = 0` initializes the counter.
- `i < 5` keeps the loop running while the condition is true.
- `i++` increments the counter after each iteration.

### Output

```
JavaScript loop iteration: 0
JavaScript loop iteration: 1
JavaScript loop iteration: 2
JavaScript loop iteration: 3
JavaScript loop iteration: 4
```

---

# 📊 Quick Comparison

| Language | Loop Syntax | Characteristics |
|-----------|------------|-----------------|
| Java | `for (int i = 0; i < 5; i++)` | Requires declaring the variable type (`int`) and manually increments the counter. |
| Python | `for i in range(5):` | Clean and concise syntax using the built-in `range()` function. |
| JavaScript | `for (let i = 0; i < 5; i++)` | Similar to Java, but uses `let` instead of a typed variable declaration. |

---

# Key Differences

### Java

- Statically typed language.
- Requires declaring the data type.
- Commonly used in enterprise applications and Android development.

### Python

- Simple and highly readable syntax.
- Automatically manages iteration.
- Ideal for scripting, automation, data science, and machine learning.

### JavaScript

- Uses syntax similar to Java.
- Commonly used for web development.
- Executes in browsers and server environments such as Node.js.

---

# Conclusion

Although Java, Python, and JavaScript use different syntax for `for` loops, they all share the same fundamental purpose: executing a block of code repeatedly.

Understanding these differences helps developers transition more easily between programming languages while recognizing each language's coding style and best practices.
