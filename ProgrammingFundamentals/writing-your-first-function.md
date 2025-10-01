# 👩🏽‍💻 Writing Your First Function

Functions are **reusable blocks of code** that perform specific tasks. Instead of repeating the same code over and over, you can define it once and use it whenever needed.

In this post, you'll learn how to write your first function in **Python**, **JavaScript**, and **Java**.

---

## 💡 What Is a Function?

Think of a function like a machine:

- You **give it input** (optional)
- It **does something**
- It may **return a result**

---

## 🐍 Python Example

```python
# Define the function
def greet(name):
    return f"Hello, {name}!"

# Call the function
message = greet("Coraline")
print(message)
````

✅ Output:
`Hello, Coraline!`

📝 In Python:

* Use `def` to define a function
* Indentation matters!
* You can return values using `return`

---

## 🌐 JavaScript Example

```javascript
// Define the function
function greet(name) {
  return "Hello, " + name + "!";
}

// Call the function
let message = greet("Jen");
console.log(message);
```

✅ Output:
`Hello, Jen!`

📝 In JavaScript:

* Use `function` keyword to define a function
* Use `return` to send a value back
* Functions can also be stored in variables or written as arrow functions

---

## ☕ Java Example

```java
public class Main {
    // Define the function
    public static String greet(String name) {
        return "Hello, " + name + "!";
    }

    public static void main(String[] args) {
        // Call the function
        String message = greet("Joel");
        System.out.println(message);
    }
}
```

✅ Output:
`Hello, Joel!`

📝 In Java:

* Functions are called **methods**
* They must be inside a **class**
* You must define the return type (`String`, `int`, `void`, etc.)

---

## 🎯 Mini Challenge

Write a function in your preferred language that:

> Takes a number as input and returns `"Even"` if it's even, or `"Odd"` if it's odd.

---

## ✅ Key Takeaways

* A function groups reusable logic into a single block
* It may accept **parameters** and return a **result**
* Helps make code **cleaner**, **easier to read**, and **maintainable**

---

## 🚀 What's Next?

Explore more on:

* Parameters vs. Arguments
* Return types and `void` functions
* Scope and variable visibility
* Arrow functions (JavaScript)
* Method overloading (Java)

---

Happy coding! 💻✨

✍️ *Written by D.Yenn*

📅 *Posted: October 1, 2025*


