# 🧠 Loops Made Easy (Java Edition)

Loops are essential in Java programming. They allow you to **repeat actions** multiple times without writing the same code again and again.

Whether you're printing numbers, processing arrays, or building logic, loops help you do it efficiently.

---

## Types of Loops in Java

Java has three main types of loops:

---

###  `for` Loop

Used when you **know in advance** how many times you want to repeat something.

```java
for (int i = 0; i < 5; i++) {
    System.out.println("Hello, Java!");
}
````

💡 This prints "Hello, Java!" 5 times.

---

###  `while` Loop

Used when you want to repeat an action **while a condition is true**.

```java
int count = 0;
while (count < 3) {
    System.out.println("Count is: " + count);
    count++;
}
```

---

###  `do-while` Loop

This loop **runs at least once**, even if the condition is false.

```java
int num = 0;
do {
    System.out.println("Number is: " + num);
    num++;
} while (num < 1);
```

---

## 🚨 Common Mistake: Infinite Loop

Be careful not to create a loop that never ends!

```java
// Warning: This will run forever
while (true) {
    System.out.println("This never stops!");
}
```

Always make sure the loop condition eventually becomes `false`.

---

## Real-Life Use Cases

* Looping through arrays or lists
* Asking for user input until valid
* Running game loops
* Generating patterns or tables

---

## 🎯 Mini Challenge

Write a Java program that prints all **even numbers** between 1 and 20:

```java
for (int i = 1; i <= 20; i++) {
    if (i % 2 == 0) {
        System.out.println(i);
    }
}
```

Try modifying it to print only **odd** numbers!

---

## 🧠 Key Takeaways

* Use `for` loops when count is known
* Use `while` for flexible conditions
* `do-while` guarantees at least one run
* Watch out for infinite loops

---

Keep practicing! Loops are the gateway to logic building in Java.
Happy coding! 

---

✍️ *Written by D.Yenn*

📅 *Posted: October 1, 2025*



