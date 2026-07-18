# Day 7 – Logarithms

> *"If exponents tell us the result of repeated multiplication, logarithms tell us how many times we multiplied."*

---

# 🎯 Learning Objective

By the end of this chapter, you will understand:

- What logarithms are.
- The relationship between exponents and logarithms.
- Basic laws of logarithms.
- Why logarithms are widely used in Machine Learning.

---

# 🤔 Why Learn Logarithms?

Logarithms simplify calculations involving very large or very small numbers.

They help us:

- Reverse exponential operations
- Measure information
- Calculate probabilities
- Build loss functions
- Improve numerical stability

Many Machine Learning algorithms rely on logarithms to make calculations easier and more accurate.

---

# 📌 What is a Logarithm?

A logarithm answers the question:

> **"To what power must the base be raised to obtain a given number?"**

General form:

```text
logₐ(b) = x
```

This means:

```text
aˣ = b
```

Example:

```text
log₂(8) = 3
```

because

```text
2³ = 8
```

---

# 🔄 Relationship Between Exponents and Logarithms

Exponential Form

```text
2³ = 8
```

Logarithmic Form

```text
log₂(8) = 3
```

Both expressions represent exactly the same relationship.

---

# 📚 Common Logarithms

## Base 10 (Common Logarithm)

```text
log₁₀(100) = 2
```

because

```text
10² = 100
```

---

## Natural Logarithm

The natural logarithm uses the special number:

```text
e ≈ 2.71828
```

Notation:

```text
ln(x)
```

Natural logarithms are used extensively in Machine Learning and Deep Learning.

---

# 📚 Laws of Logarithms

## 1️⃣ Product Rule

```text
log(a × b)

=

log(a) + log(b)
```

Example:

```text
log(100 × 10)

=

log(100)

+

log(10)
```

---

## 2️⃣ Quotient Rule

```text
log(a / b)

=

log(a)

-

log(b)
```

---

## 3️⃣ Power Rule

```text
log(aⁿ)

=

n × log(a)
```

Example:

```text
log(10³)

=

3 × log(10)
```

---

# 🤖 Machine Learning Connection

Logarithms appear in many important ML concepts.

---

## 1️⃣ Cross-Entropy Loss

Classification models often use **Cross-Entropy Loss**.

This loss function uses logarithms because they heavily penalize confident but incorrect predictions.

Example:

If a model predicts the correct class with high probability, the loss is small.

If it predicts the wrong class with high confidence, the loss becomes much larger.

---

## 2️⃣ Information Theory

Claude Shannon introduced the concept of **information** using logarithms.

Entropy, a measure of uncertainty, is calculated using logarithmic functions.

Entropy is used in:

- Decision Trees
- Information Gain
- Random Forests

---

## 3️⃣ Naive Bayes Classifier

Naive Bayes multiplies many probabilities.

Since multiplying many small numbers can cause computational issues, logarithms convert multiplication into addition.

Instead of:

```text
P₁ × P₂ × P₃ × ...
```

we calculate:

```text
log(P₁)

+

log(P₂)

+

log(P₃)
```

This is faster and numerically more stable.

---

## 4️⃣ Neural Networks

Many optimization algorithms use logarithmic calculations to improve training and reduce numerical errors.

---

# 🌍 Real-World Example

Imagine an email spam classifier.

Probability that an email is spam:

```text
0.99
```

Probability that it is not spam:

```text
0.01
```

Loss functions use logarithms to evaluate how confident these predictions are and guide the model toward better performance.

---

# 📌 Did You Know?

Google's original **PageRank** algorithm and many ranking algorithms use logarithmic concepts to handle very large numbers efficiently.

---

# 🎓 Interview Insight

Common interview questions include:

- What is the difference between exponentials and logarithms?
- Why is the natural logarithm used in Machine Learning?
- Why do loss functions use logarithms instead of simple subtraction?

Understanding logarithms makes advanced ML topics much easier.

---

# 💻 Python Playground

```python
import math

print(math.log2(8))
print(math.log10(100))
print(math.log(math.e))
```

Output

```text
3.0
2.0
1.0
```

---

# 🧩 Visual Intuition

Exponent

```text
2³ = 8
```

↓

Logarithm

```text
log₂(8) = 3
```

Think of a logarithm as asking:

> **"What power gives me this number?"**

---

# 📖 Summary

Today we learned:

- Logarithms are the inverse of exponents.
- They simplify calculations involving large and small numbers.
- Machine Learning uses logarithms in loss functions, entropy, and probability.
- Logarithms improve computational efficiency and numerical stability.

---

# 📝 Quick Revision

- Logarithm is the inverse of exponentiation.
- `logₐ(b) = x` means `aˣ = b`.
- Natural logarithm (`ln`) uses base **e**.
- Logarithms convert multiplication into addition.
- Cross-Entropy Loss and Entropy rely on logarithms.

---

# ❓ Interview Questions

1. What is a logarithm?
2. Explain the relationship between exponents and logarithms.
3. Why are logarithms used in Cross-Entropy Loss?
4. What is the difference between `log`, `log₂`, and `ln`?
5. Why do Naive Bayes algorithms use logarithms?

---

# 🧠 Practice Problems

### 1.

Find:

```text
log₂(16)
```

✅ Answer:

```text
4
```

---

### 2.

Find:

```text
log₁₀(1000)
```

✅ Answer:

```text
3
```

---

### 3.

Convert into logarithmic form:

```text
5² = 25
```

✅ Answer:

```text
log₅(25) = 2
```

---

# 🚀 What's Next?

➡️ **Day 8 – Algebra Fundamentals**

We'll learn how algebra helps describe relationships between variables and forms the mathematical foundation of Machine Learning models such as **Linear Regression**.

---

# 📚 References

- Mathematics for Machine Learning — Marc Peter Deisenroth, A. Aldo Faisal & Cheng Soon Ong
- Deep Learning by Ian Goodfellow
- Pattern Recognition and Machine Learning — Christopher Bishop
- Python `math` Module Documentation

---

> *"Logarithms transform complex multiplication into simple addition—one reason they are indispensable in modern Machine Learning."*
