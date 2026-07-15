# Day 4 – Fractions, Decimals & Percentages

> *"Every probability, accuracy score, and prediction confidence in Machine Learning is built on fractions, decimals, and percentages."*

---

# 🎯 Learning Objective

By the end of this chapter, you will understand:

- What fractions, decimals, and percentages are.
- How to convert between them.
- Why these concepts are important in Machine Learning.
- Where they appear in real-world AI applications.

---

# 🤔 Why Learn Fractions, Decimals & Percentages?

Although these concepts are introduced in school mathematics, they play an important role in Data Science and Machine Learning.

They help us:

- Represent probabilities
- Measure model performance
- Normalize data
- Understand prediction confidence
- Interpret evaluation metrics

Many values produced by ML algorithms are expressed as decimals or percentages.

---

# 1️⃣ Fractions

A **fraction** represents a part of a whole.

General form:

```text
Numerator
──────────
Denominator
```

Example:

```text
3/4
```

This means **3 parts out of 4 equal parts.**

---

## Example

Suppose a dataset contains:

- 80 cats
- 20 dogs

Fraction of dogs:

```text
20/100 = 1/5
```

---

# 2️⃣ Decimals

Decimals are another way to represent fractions.

Examples:

| Fraction | Decimal |
|-----------|----------|
| 1/2 | 0.5 |
| 1/4 | 0.25 |
| 3/4 | 0.75 |
| 1/10 | 0.1 |

Decimals are heavily used in Machine Learning because computers perform calculations using decimal values.

---

## Example

Probability:

```text
0.87
```

means

87% chance.

---

# 3️⃣ Percentages

Percentage means **"per hundred."**

Formula:

Percentage = (Part / Total) × 100

---

## Example

Correct Predictions = 920

Total Predictions = 1000

Accuracy:

```text
(920 / 1000) × 100

= 92%
```

This is one of the most common calculations in Machine Learning.

---

# 🔄 Conversion Table

| Fraction | Decimal | Percentage |
|-----------|----------|------------|
| 1/2 | 0.5 | 50% |
| 1/4 | 0.25 | 25% |
| 3/4 | 0.75 | 75% |
| 1/5 | 0.2 | 20% |
| 9/10 | 0.9 | 90% |

---

# 🤖 Machine Learning Connection

Fractions, decimals, and percentages appear almost everywhere in ML.

### Model Accuracy

```text
Accuracy = 96.5%
```

---

### Prediction Probability

A classifier predicts:

```text
Dog = 0.94

Cat = 0.06
```

This means the model is **94% confident** that the image contains a dog.

---

### Dataset Split

Most ML datasets are divided into:

```text
80% Training

20% Testing
```

Sometimes:

```text
70%

15%

15%
```

Training / Validation / Testing

---

### Data Normalization

Suppose exam marks are:

```text
95 / 100
```

Normalized value:

```text
0.95
```

Machine Learning models often work better when data is represented as decimals.

---

# 🌍 Real-World Example

Suppose you build a spam detection model.

Results:

| Emails | Count |
|---------|------|
| Total Emails | 5000 |
| Correct Predictions | 4850 |

Accuracy:

```text
4850 / 5000

= 0.97

= 97%
```

This single percentage tells us how well the model performs.

---

# 📌 Did You Know?

Many Machine Learning libraries return probabilities instead of direct answers.

Example:

```text
Cat → 0.82

Dog → 0.18
```

The model chooses the class with the highest probability.

---

# 🎓 Interview Insight

Common interview questions:

- Why do ML models return probabilities?
- Why is accuracy expressed as a percentage?
- Why is data normalized between 0 and 1?

These questions are directly related to fractions and decimals.

---

# 💻 Python Playground

```python
correct_predictions = 920
total_predictions = 1000

accuracy = (correct_predictions / total_predictions) * 100

print(f"Model Accuracy: {accuracy:.2f}%")
```

Output

```text
Model Accuracy: 92.00%
```

---

# 📖 Summary

Today we learned:

- Fractions represent parts of a whole.
- Decimals are numerical representations of fractions.
- Percentages represent values out of 100.
- Machine Learning uses these concepts to calculate probabilities, accuracy, confidence scores, and dataset splits.

---

# 🚀 What's Next?

➡️ **Day 5 – Ratios & Proportions**

We'll learn how ratios help compare data, balance datasets, and understand class distributions in Machine Learning.

---

# 📚 References

- Mathematics for Machine Learning — Marc Peter Deisenroth, A. Aldo Faisal & Cheng Soon Ong
- Python Documentation
- Scikit-learn User Guide

---

> *"Machine Learning is not only about predicting correctly—it's about measuring how well those predictions perform."*
