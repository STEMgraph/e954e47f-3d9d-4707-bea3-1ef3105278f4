<!---
{
  "id": "e954e47f-3d9d-4707-bea3-1ef3105278f4",
  "depends_on": [],
  "author": "Stephan Bökelmann",
  "first_used": "2025-03-27",
  "keywords": ["mathematics", "cartesian product", "function", "mapping", "tuples"]
}
--->

# Cartesian Products and Functions of Multiple Inputs

## 1) Introduction
In the previous sheet, we explored the concept of a function as a mapping from one set (the domain) to another set (the codomain). But what if we want to model situations where a function depends on **two** inputs? In that case, we turn to the idea of the **Cartesian product**.

> **Definition:**  
> The **Cartesian product** of two sets A and B, written as A × B, is the set of **all ordered pairs** (a, b) where a is in A and b is in B.

For example:
```
A = {1, 2}
B = {x, y}
A × B = { (1, x), (1, y), (2, x), (2, y) }
```

Each element of the Cartesian product is a **tuple** — a pair of elements where the **order matters**.

---

### 1.0.1) Visualising the Cartesian Product
We can draw the Cartesian product as a grid or matrix:

```
       x     y
    +-----+-----+
 1  |1, x|1, y|
    +-----+-----+
 2  |2, x|2, y|
    +-----+-----+
```

Each cell in the table represents a pair (a, b) in A × B.

This is the domain for functions with **two inputs**.

---

### 1.0.2) Functions with Two Inputs
A function of two variables can now be defined as:

```
f: A × B → C
```

Example: Let A = {1, 2}, B = {10, 20}, and define:
```
f(a, b) = a + b
```

Then the function maps:
- f(1, 10) = 11
- f(1, 20) = 21
- f(2, 10) = 12
- f(2, 20) = 22

Each pair in A × B is mapped to a unique value in C.

---

### 1.1) Further Readings and Other Sources

- Spivak. *Calculus* – Chapter on functions of several variables.
- S. Mac Lane. *Categories for the Working Mathematician* (for advanced readers)
- [Cartesian Products explained visually (YouTube)](https://www.youtube.com/watch?v=9Q6XopAU3Ig)
- [Interactive Tuple Pairing Tool (Visualgo)](https://visualgo.net/en/heap) *(used creatively to visualize pairings)*


## 2) Tasks

1. **Enumerate the Cartesian Product**:  
Let A = {a, b, c}, B = {1, 2}. Write out all elements of A × B.

2. **Grid Drawing**:  
Draw the Cartesian product A × B from task 1 as a table or grid, with A along the vertical axis and B along the horizontal axis.

3. **Define a Function on a Cartesian Product**:  
Let A = {0, 1}, B = {0, 1}, and define a function f: A × B → N by:
```
f(a, b) = a * 2 + b
```
List the output of all possible pairs.

## 3) Questions
1. Why is the **order** of elements in a tuple important in the Cartesian product?
2. Can you think of real-world examples where data naturally forms **pairs**?
3. What changes if you consider B × A instead of A × B?
4. How would you describe a function of three inputs using Cartesian products?
5. Take a look at task 3 once again: What kind of values do you get? Do these resemble anything familiar from binary numbers?

---

## 4) Final Advice
Cartesian products allow us to model more complex input structures. Once you understand how sets of pairs work, many programming and mathematical ideas become more intuitive: 2D arrays, coordinate systems, nested loops, and even database joins rely on this concept. When working with such functions, keep track of your domains, and always pay attention to the order in your tuples!

