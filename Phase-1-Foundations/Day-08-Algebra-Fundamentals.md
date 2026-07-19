# Day 8 – Algebra Fundamentals

> *"Algebra is the language of Machine Learning. Every ML model is essentially an equation waiting to learn the right values."*

---

# 🎯 Learning Objective

By the end of this chapter, you will understand:

- What algebra is.
- Variables, constants, and expressions.
- Algebraic equations.
- Why algebra is the backbone of Machine Learning.

---

# 🤔 Why Learn Algebra?

Arithmetic deals with numbers.

Algebra deals with **unknown values**.

Instead of solving only:

```text
5 + 3 = 8
```

Algebra allows us to solve problems like:

```text
x + 3 = 8
```

where **x** is unknown.

Machine Learning models also try to find unknown values (parameters) that best fit the data.

---

# 📌 What is Algebra?

Algebra is a branch of mathematics that uses **symbols and variables** to represent numbers and relationships.

Instead of writing specific values, we use letters like:

```text
x

y

z

a

b
```

These symbols make equations more general and reusable.

---

# 🔠 Variables

A **variable** is a symbol that represents an unknown or changing value.

Examples:

```text
x = 5

y = 12
```

Variables are commonly used in programming and Machine Learning.

---

# 🔢 Constants

A **constant** is a fixed value that never changes.

Examples:

```text
5

10

3.14

100
```

In the equation:

```text
x + 5 = 12
```

- `x` is the variable.
- `5` and `12` are constants.

---

# 🧮 Algebraic Expressions

An **expression** is a combination of variables, numbers, and mathematical operations.

Examples:

```text
2x + 3
```

```text
5a - 7
```

```text
x² + 2x + 1
```

Expressions do **not** contain an equals sign (`=`).

---

# 📐 Algebraic Equations

An **equation** states that two expressions are equal.

General form:

```text
Expression = Expression
```

Example:

```text
2x + 4 = 10
```

To solve:

```text
2x = 10 - 4

2x = 6

x = 3
```

Always perform the same operation on both sides of the equation to keep it balanced.

---

# 🔄 Expressions vs Equations

| Expression | Equation |
|------------|----------|
| `2x + 3` | `2x + 3 = 7` |
| No equals sign | Contains an equals sign |
| Represents a value | States equality |

---

# 🤖 Machine Learning Connection

Algebra is used throughout Machine Learning.

## 1️⃣ Linear Regression

The simplest ML model is written as:

```text
y = mx + c
```

Where:

- `x` → Input feature
- `m` → Slope (weight)
- `c` → Bias (intercept)
- `y` → Prediction

The model learns the best values of **m** and **c**.

---

## 2️⃣ Neural Networks

A neuron performs calculations like:

```text
Output = Weight × Input + Bias
```

This is simply an algebraic equation.

---

## 3️⃣ Feature Engineering

Suppose:

```text
Age = x

Experience = y
```

A new feature could be:

```text
x + y
```

or

```text
2x + 3y
```

Feature engineering often combines variables using algebra.

---

# 🌍 Real-World Example

Suppose you want to predict a student's marks based on study hours.

Model:

```text
Marks = 8 × Study Hours + 20
```

If a student studies:

```text
5 hours
```

Then:

```text
Marks = 8 × 5 + 20

= 60
```

This simple equation is a Machine Learning model.

---

# 📌 Did You Know?

Large Language Models contain **billions of parameters** (variables). Training is the process of adjusting these variables so the model makes accurate predictions.

---

# 🎓 Interview Insight

Common interview questions:

- What is the difference between a variable and a constant?
- What is an algebraic expression?
- What is an equation?
- Why is algebra important in Machine Learning?

---

# 💻 Python Playground

```python
study_hours = 5

marks = 8 * study_hours + 20

print("Predicted Marks:", marks)
```

Output

```text
Predicted Marks: 60
```

---

# 🧩 Visual Intuition

Equation

```text
2x + 4 = 10
```

↓

Subtract 4

```text
2x = 6
```

↓

Divide by 2

```text
x = 3
```

Think of solving an equation as balancing a weighing scale—whatever you do to one side, you must do to the other.

---

# 📖 Summary

Today we learned:

- Algebra uses symbols to represent numbers.
- Variables represent unknown values.
- Constants are fixed values.
- Expressions combine variables and numbers.
- Equations express equality.
- Machine Learning models are built using algebraic equations.

---

# 📝 Quick Revision

- Variable → Unknown value
- Constant → Fixed value
- Expression → No equals sign
- Equation → Contains an equals sign
- Linear Regression is an algebraic equation.

---

# ❓ Interview Questions

1. What is algebra?
2. What is the difference between a variable and a constant?
3. What is an algebraic expression?
4. What is an equation?
5. How is algebra used in Machine Learning?

---

# 🧠 Practice Problems

### 1.

Solve:

```text
x + 7 = 15
```

✅ Answer:

```text
x = 8
```

---

### 2.

Solve:

```text
3x = 18
```

✅ Answer:

```text
x = 6
```

---

### 3.

If

```text
y = 5x + 2
```

Find **y** when:

```text
x = 4
```

✅ Answer:

```text
y = 22
```

---

# 🔮 Where You'll Use This Later

| Topic | ML Application |
|--------|----------------|
| Variables | Model parameters (weights & biases) |
| Equations | Linear Regression |
| Expressions | Feature engineering |
| Unknown values | Model training |
| Solving equations | Optimization |

---

# 🚀 What's Next?

➡️ **Day 9 – Functions**

We'll learn how functions map inputs to outputs and why every Machine Learning model—from Linear Regression to Neural Networks—is fundamentally a mathematical function.

---

# 📚 References

- Mathematics for Machine Learning — Marc Peter Deisenroth, A. Aldo Faisal & Cheng Soon Ong
- Linear Algebra and Its Applications — Gilbert Strang
- Python Documentation

---

> *"Learning algebra means learning the language that every Machine Learning model speaks."*
