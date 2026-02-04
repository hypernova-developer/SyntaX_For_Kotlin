# SyntaX for Kotlin (bettersyntax.kt) 🚀

**SyntaX for Kotlin** is a lightweight, high-performance utility library designed to bring the minimalist and expressive nature of Python to the powerful Kotlin ecosystem. 

## 🌟 Key Features
* **Expressive Syntax:** Familiar and simplified functions like print, input, and randint.
* **Pure Performance:** Optimized with Kotlin's tailrec functions and efficient operations.
* **Extension-Powered:** Enhances standard Kotlin collections with custom sumAll and averageAll capabilities.

## 💻 Technical Details
The library leverages Kotlin's Top-Level Functions to eliminate the need for redundant class wrapping. It is specifically designed to be memory efficient, utilizing Kotlin's **lazy initialization** for resources.

## Development Comparison

| Feature | Standard Kotlin / JVM | SyntaX for Kotlin |
| :--- | :--- | :--- |
| Output | println("x: $x") | print(x, y) |
| User Input | Scanner(System.in).nextLine() | val s = input("Name: ") |
| Random Number | (min..max).random() | randint(min, max) |
| Sleep/Wait | Thread.sleep(1000) | sleep(1.0) |
| List Sum | list.sumOf { it.toDouble() } | list.sumAll() |
| Factorial | Manual recursion | factorial(n) |

## 👨‍💻 Programmer
**hypernova-developer**

---
*"The monster's running wild inside of me."* 🐆
