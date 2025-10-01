#  Intro to Arrays

Arrays are one of the most important data structures in programming. They let you **store multiple values in a single variable**, making your code cleaner and more powerful.

---

## What Is an Array?

An **array** is a collection of values stored in a specific order.

### Examples:

**Python:**

```python
fruits = ["apple", "banana", "cherry"]
````

**JavaScript:**

```javascript
let fruits = ["apple", "banana", "cherry"];
```

**Java:**

```java
String[] fruits = {"apple", "banana", "cherry"};
```

Each item has a **position** called an **index**, starting at 0.

---

## Accessing Array Elements

To get an item from an array, use its index:

**Python:**

```python
print(fruits[0])  # Output: apple
```
**JavaScript:**
```javascript
console.log(fruits[1]);  // Output: banana
```
**Java:**
```java
System.out.println(fruits[2]);  // Output: cherry
```

---

##  Changing Values

You can update an array element by assigning a new value to an index:

```python
fruits[1] = "blueberry"
```

---

## Looping Through Arrays

### Python:

```python
for fruit in fruits:
    print(fruit)
```

### JavaScript:

```javascript
for (let i = 0; i < fruits.length; i++) {
    console.log(fruits[i]);
}
```

### Java:

```java
for (String fruit : fruits) {
    System.out.println(fruit);
}
```

---

## Array Indexing Starts at 0

This is a common source of confusion!

```text
Index:    0        1        2
Array: ["apple", "banana", "cherry"]
```

Trying to access index `3` in this case would cause an error — the array only has 3 elements (0, 1, 2).

---

## 🎯 Mini Challenge

Try this in your favorite language:

> Create an array of your top 5 favorite songs, then print them out one by one.

---

## ✅ Key Takeaways

* Arrays store multiple values in a single variable
* Indexes start at 0
* You can loop through arrays to process each item
* Arrays are the foundation for more advanced structures like lists, stacks, and queues

---


✍️ *Written by D.Yenn*

📅 *Posted: October 1, 2025*



