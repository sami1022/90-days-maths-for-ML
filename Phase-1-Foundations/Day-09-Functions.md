# Day 9 – Functions

> *"A Machine Learning model is nothing more than a mathematical function that learns how to transform inputs into meaningful outputs."*

---

# 🎯 Learning Objective

By the end of this chapter, you will understand:

- What a function is.
- Inputs, outputs, domain, and range.
- Function notation.
- Different types of functions.
- Why functions are the heart of Machine Learning.

---

# 🤔 Why Learn Functions?

Functions are everywhere in mathematics.

They describe relationships between variables.

In Machine Learning, every model is a function that takes **input data** and produces an **output prediction**.

Examples:

- Predict house prices
- Recognize faces
- Detect spam emails
- Translate languages
- Recommend movies

All of these are functions.

---

# 📌 What is a Function?

A **function** is a mathematical rule that maps each input to exactly one output.

Think of a function as a machine.

```text
Input

↓

[ Function ]

↓

Output
```

Every valid input produces exactly one output.

---

# 📖 Function Notation

Functions are commonly written as:

```text
f(x)
```

Where:

- **f** → Function name
- **x** → Input

Example:

```text
f(x) = 2x + 3
```

If:

```text
x = 5
```

Then:

```text
f(5)

= 2 × 5 + 3

= 13
```

---

# 🔢 Input and Output

Consider:

```text
f(x) = x²
```

| Input (x) | Output f(x) |
|-----------|------------|
| 1 | 1 |
| 2 | 4 |
| 3 | 9 |
| 4 | 16 |
| 5 | 25 |

Each input has exactly one output.

That is what makes it a function.

---

# 📌 Domain and Range

## Domain

The **domain** is the set of all possible input values.

Example:

```text
f(x) = x²
```

Possible inputs:

```text
-3

-2

-1

0

1

2

3
```

These belong to the domain.

---

## Range

The **range** is the set of outputs produced by the function.

For:

```text
f(x)=x²
```

Outputs are:

```text
0

1

4

9

16
```

Notice that negative outputs never occur.

---

# 📊 Types of Functions

## 1️⃣ Linear Function

```text
f(x)=mx+c
```

Example:

```text
f(x)=3x+2
```

Used in:

- Linear Regression
- Basic predictive models

---

## 2️⃣ Quadratic Function

```text
f(x)=x²
```

Produces a curved graph.

Useful for understanding nonlinear relationships.

---

## 3️⃣ Exponential Function

```text
f(x)=2ˣ
```

Used in:

- Neural Networks
- Probability
- Softmax
- Population growth

---

## 4️⃣ Logarithmic Function

```text
f(x)=log(x)
```

Used in:

- Cross-Entropy Loss
- Entropy
- Information Theory

---

# 🤖 Machine Learning Connection

Every Machine Learning algorithm is a function.

Example:

Suppose we want to predict house prices.

Function:

```text
Price = f(Size)
```

Input:

```text
1200 sq.ft
```

↓

Function

↓

Output:

```text
₹60,00,000
```

The goal of Machine Learning is to learn the best function from data.

---

# 🌍 Real-World Example

Imagine an AI model that predicts exam scores.

Function:

```text
Marks = f(Study Hours)
```

Input:

```text
6 hours
```

↓

Model

↓

Prediction:

```text
82 marks
```

The model learns this relationship by analyzing past data.

---

# 📌 Did You Know?

Modern AI models like ChatGPT are extremely complex mathematical functions containing billions of learned parameters.

Despite their complexity, they still follow the same principle:

```text
Input

↓

Function

↓

Output
```

---

# 🎓 Interview Insight

Common interview questions:

- What is a function?
- What is the difference between a function and an equation?
- What are domain and range?
- Why are Machine Learning models considered functions?

---

# 💻 Python Playground

```python
def predict_marks(hours):
    return 8 * hours + 20

study_hours = 5

print("Predicted Marks:", predict_marks(study_hours))
```

Output

```text
Predicted Marks: 60
```

---

# 🧩 Visual Intuition

```text
Study Hours

      │

      ▼

+----------------+
|   Function     |
| f(x)=8x + 20   |
+----------------+

      │

      ▼

Predicted Marks
```

A function acts like a machine:

- Takes an input.
- Applies a rule.
- Produces an output.

---

# 🔬 ML Spotlight – Activation Functions

Neural Networks use **activation functions** to introduce non-linearity.

Common activation functions:

- Sigmoid
- ReLU
- Tanh
- Softmax

Without activation functions, deep neural networks would behave like simple linear models.

You'll study these in detail later in the roadmap.

---

# 📖 Summary

Today we learned:

- A function maps every input to exactly one output.
- Functions have a domain and a range.
- Functions describe relationships between variables.
- Every Machine Learning model is fundamentally a mathematical function.

---

# 📝 Quick Revision

- Function → Maps input to output.
- Domain → All possible inputs.
- Range → All possible outputs.
- `f(x)` is standard function notation.
- Machine Learning learns the best function from data.

---

# ❓ Interview Questions

1. What is a function?
2. What is function notation?
3. What is the difference between domain and range?
4. Why are ML models considered mathematical functions?
5. Give examples of functions used in Machine Learning.

---

# 🧠 Practice Problems

### 1.

Given:

```text
f(x)=3x+4
```

Find:

```text
f(5)
```

✅ Answer:

```text
19
```

---

### 2.

Given:

```text
f(x)=x²
```

Find:

```text
f(6)
```

✅ Answer:

```text
36
```

---

### 3.

If:

```text
f(x)=2x−1
```

Find:

```text
f(10)
```

✅ Answer:

```text
19
```

---

# 🔮 Where You'll Use This Later

| Mathematical Concept | ML Application |
|-----------------------|----------------|
| Functions | Every ML model |
| Linear Function | Linear Regression |
| Non-linear Function | Neural Networks |
| Logarithmic Function | Cross-Entropy Loss |
| Exponential Function | Softmax, Sigmoid |

---

# 🚀 What's Next?

➡️ **Day 10 – Graphs of Functions**

We'll learn how to visualize functions using graphs and understand how Machine Learning identifies patterns, trends, and relationships in data.

---

# 📚 References

- Mathematics for Machine Learning — Marc Peter Deisenroth, A. Aldo Faisal & Cheng Soon Ong
- Linear Algebra and Its Applications — Gilbert Strang
- Deep Learning — Ian Goodfellow
- Python Documentation

---

> *"Machine Learning is the art of discovering the function that best explains the relationship hidden inside data."*
