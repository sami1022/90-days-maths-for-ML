# Day 5 – Ratios & Proportions

> *"Machine Learning is all about finding relationships, and ratios are one of the simplest ways to compare them."*

---

# 🎯 Learning Objective

By the end of this chapter, you will understand:

- What ratios and proportions are.
- The difference between them.
- How they help compare quantities.
- Why they are important in Machine Learning and Data Science.

---

# 🤔 Why Learn Ratios & Proportions?

Machine Learning often deals with comparing values rather than looking at them individually.

Examples include:

- Class distribution
- Dataset splitting
- Feature scaling
- Image dimensions
- Probability
- Evaluation metrics

Ratios help us understand these comparisons.

---

# 📌 What is a Ratio?

A **ratio** compares two quantities.

It tells us how many times one value contains or relates to another.

General form:

```text
A : B
```

Example:

Suppose a classroom has:

- 18 boys
- 12 girls

The ratio of boys to girls is:

```text
18 : 12
```

After simplification:

```text
3 : 2
```

This means for every **3 boys**, there are **2 girls**.

---

# 📌 What is a Proportion?

A **proportion** states that two ratios are equal.

Example:

```text
2 : 4 = 4 : 8
```

Because

```text
2/4 = 4/8 = 0.5
```

Both ratios represent the same relationship.

---

# 🔍 Ratio vs Proportion

| Ratio | Proportion |
|--------|------------|
| Compares two quantities | Compares two ratios |
| Example: 3:2 | Example: 3:2 = 6:4 |
| Shows relationship | Shows equality of relationships |

---

# 📊 Real-Life Examples

### Student Ratio

```text
Boys : Girls

60 : 40

= 3 : 2
```

---

### Recipe

```text
Rice : Water

1 : 2
```

Every cup of rice requires two cups of water.

---

### Screen Resolution

```text
1920 × 1080

Aspect Ratio

16 : 9
```

Most monitors and televisions use this ratio.

---

# 🤖 Ratios in Machine Learning

Machine Learning uses ratios in many places.

---

## 1️⃣ Dataset Split

One common practice is:

```text
Training : Testing

80 : 20
```

Sometimes datasets are divided as:

```text
70 : 15 : 15

Training
Validation
Testing
```

This ensures the model is trained and evaluated fairly.

---

## 2️⃣ Class Distribution

Suppose a dataset contains:

```text
900 Cats

100 Dogs
```

Ratio:

```text
9 : 1
```

This is called an **imbalanced dataset**.

Such datasets can cause biased Machine Learning models.

---

## 3️⃣ Image Aspect Ratio

Images are resized before training.

Common ratios:

```text
1 : 1

4 : 3

16 : 9
```

Maintaining aspect ratio avoids image distortion.

---

## 4️⃣ Feature Scaling

Suppose:

```text
Age

18–60

Salary

20,000–2,000,000
```

The salary values dominate the age values.

Scaling adjusts their proportions so each feature contributes fairly.

---

# 🌍 Real-World Example

Imagine building a fraud detection model.

Dataset:

```text
Legitimate Transactions

98%

Fraud Transactions

2%
```

Ratio:

```text
98 : 2

= 49 : 1
```

This imbalance makes fraud detection challenging because the model sees far fewer fraud examples.

---

# 📌 Did You Know?

Many real-world Machine Learning datasets are **imbalanced**.

For example:

- Credit card fraud
- Disease diagnosis
- Spam detection

The rare class is often the one we care about most.

---

# 🎓 Interview Insight

Common interview questions include:

- What is an imbalanced dataset?
- Why is an 80:20 train-test split commonly used?
- Why is feature scaling important?

Understanding ratios helps answer these questions.

---

# 💻 Python Playground

```python
cats = 900
dogs = 100

ratio = cats / dogs

print(f"Cat : Dog = {ratio}:1")
```

Output

```text
Cat : Dog = 9.0:1
```

---

# 🧩 Visual Intuition

Dataset Split

```text
Training Data

████████░░

80%
```

Testing Data

```text
██░░░░░░░░

20%
```

---

Class Distribution

```text
Cats

█████████░

90%
```

Dogs

```text
█░░░░░░░░░

10%
```

---

# 📖 Summary

Today we learned:

- A ratio compares two quantities.
- A proportion states that two ratios are equal.
- Ratios are widely used in dataset splitting, feature scaling, and class distribution.
- Understanding ratios helps build better Machine Learning models.

---

# 🚀 What's Next?

➡️ **Day 6 – Exponents & Powers**

We'll learn why exponential growth appears in AI, deep learning, optimization, and computational complexity.

---

# 📚 References

- Mathematics for Machine Learning — Marc Peter Deisenroth, A. Aldo Faisal & Cheng Soon Ong
- Introduction to Machine Learning
- Scikit-learn Documentation

---

> *"Machine Learning is not only about learning patterns—it is also about understanding the proportions within the data."*
