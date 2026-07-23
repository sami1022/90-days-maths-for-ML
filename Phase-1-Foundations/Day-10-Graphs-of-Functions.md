# Day 10 – Graphs of Functions

> *"A graph turns mathematical equations into pictures, making patterns easier to understand."*

---

# 🎯 Learning Objective

By the end of this chapter, you will understand:

- What the Cartesian Coordinate System is.
- How to plot points.
- How graphs represent functions.
- Why graphs are important in Machine Learning.

---

# 🤔 Why Learn Graphs?

Imagine trying to understand thousands of data points only by looking at numbers.

It would be difficult.

Graphs help us:

- Identify trends
- Detect patterns
- Find outliers
- Understand relationships between variables

Machine Learning practitioners use graphs almost every day to analyze data and evaluate models.

---

# 📌 The Cartesian Coordinate System

A graph is drawn using two perpendicular lines called **axes**.

```text
        y-axis
          ↑
          |
          |
----------+----------→ x-axis
          |
          |
          ↓
```

- **X-axis** → Horizontal axis
- **Y-axis** → Vertical axis
- **Origin (0,0)** → The point where both axes meet

---

# 📍 Coordinates

Every point on a graph is represented as:

```text
(x, y)
```

Example:

```text
(2, 5)
```

means:

- Move **2 units** along the x-axis.
- Move **5 units** upward on the y-axis.

---

# 📈 Plotting a Function

Consider the function:

```text
f(x) = 2x + 1
```

Let's calculate a few values.

| x | y = 2x + 1 |
|---|------------|
| 0 | 1 |
| 1 | 3 |
| 2 | 5 |
| 3 | 7 |
| 4 | 9 |

Plotting these points gives a straight line.

```text
y

9 |                         ●
8 |
7 |                    ●
6 |
5 |               ●
4 |
3 |          ●
2 |
1 |     ●
0 +--------------------------------→ x
    0   1   2   3   4
```

---

# 📊 Types of Graphs

## 1️⃣ Linear Graph

Equation:

```text
y = mx + c
```

Characteristics:

- Straight line
- Constant slope
- Used in Linear Regression

---

## 2️⃣ Quadratic Graph

Equation:

```text
y = x²
```

Shape:

```text
      ●
    ●   ●
  ●       ●
●           ●
```

Characteristics:

- U-shaped curve
- Non-linear relationship

---

## 3️⃣ Exponential Graph

Equation:

```text
y = 2ˣ
```

Characteristics:

- Starts slowly
- Grows rapidly
- Common in Deep Learning and probability

---

# 📈 Understanding Trends

Graphs help us identify how variables change.

### Positive Trend

```text
Hours Studied ↑

Marks ↑
```

More study hours generally lead to higher marks.

---

### Negative Trend

```text
Speed ↑

Travel Time ↓
```

Increasing speed usually decreases travel time.

---

### No Clear Trend

Some datasets have no obvious relationship.

Graphs help reveal whether a pattern exists.

---

# 🤖 Machine Learning Connection

Graphs are used throughout the ML workflow.

## 1️⃣ Data Visualization

Before training a model, data scientists visualize the dataset.

They look for:

- Missing values
- Outliers
- Trends
- Correlations

---

## 2️⃣ Linear Regression

A regression model fits the **best line** through data points.

```text
●

     ●

          ●

              ●

-------------------------
Best Fit Line
```

---

## 3️⃣ Training Curves

During training, we plot:

- Loss vs Epochs
- Accuracy vs Epochs

These graphs show whether the model is learning.

---

## 4️⃣ Decision Boundaries

Classification models create graphs that separate different classes.

For example:

```text
Cats

************

------------

Dogs
```

---

# 🌍 Real-World Example

Imagine predicting house prices.

| Size (sq.ft.) | Price (₹ Lakhs) |
|---------------|-----------------|
| 800 | 30 |
| 1200 | 45 |
| 1600 | 60 |
| 2000 | 78 |

Plotting these values shows a clear upward trend.

This trend helps the model learn how house prices change with size.

---

# 📌 Did You Know?

Data scientists spend a significant amount of time exploring and visualizing data before training models.

Good visualizations often reveal issues that raw numbers cannot.

---

# 🎓 Interview Insight

Common interview questions:

- Why is data visualization important?
- What is the difference between linear and nonlinear graphs?
- Why do we plot loss and accuracy curves?
- What is a scatter plot?

---

# 💻 Python Playground

```python
import matplotlib.pyplot as plt

x = [0, 1, 2, 3, 4]
y = [1, 3, 5, 7, 9]

plt.plot(x, y, marker='o')
plt.title("Linear Function")
plt.xlabel("x")
plt.ylabel("y")
plt.grid(True)
plt.show()
```

---

# 🧩 Visual Intuition

```text
Input (x)

↓

Function

↓

Output (y)

↓

Graph

↓

Understand the Pattern
```

A graph transforms numbers into visual insights.

---

# 🔬 ML Spotlight – Scatter Plots

Scatter plots are one of the most commonly used visualizations in Machine Learning.

Example:

```text
Price

|

|           ●

|      ●

|   ●

|●_____________________

        Size
```

Scatter plots help identify:

- Trends
- Clusters
- Outliers
- Correlations

They are widely used before building predictive models.

---

# 📖 Summary

Today we learned:

- Graphs visually represent mathematical functions.
- The Cartesian plane consists of x-axis and y-axis.
- Graphs reveal trends and relationships.
- Machine Learning relies heavily on graphs for understanding data and evaluating models.

---

# 📝 Quick Revision

- X-axis → Horizontal
- Y-axis → Vertical
- Coordinates → (x, y)
- Linear graph → Straight line
- Graphs help identify patterns in data.

---

# ❓ Interview Questions

1. What is the Cartesian Coordinate System?
2. What is the origin?
3. What is a scatter plot?
4. Why are graphs important in Machine Learning?
5. What is the difference between linear and nonlinear graphs?

---

# 🧠 Practice Problems

### 1.

Plot the points:

```text
(1,2)

(2,4)

(3,6)

(4,8)
```

What type of graph is formed?

✅ **Answer:** Linear graph.

---

### 2.

For:

```text
y = x²
```

Find:

```text
y

when

x = 5
```

✅ **Answer:**

```text
25
```

---

### 3.

What are the coordinates of the origin?

✅ **Answer:**

```text
(0,0)
```

---

# 📚 Common Mistakes

❌ Confusing the x-axis with the y-axis.

❌ Assuming every graph is a straight line.

❌ Ignoring the scale of the axes when interpreting graphs.

❌ Believing correlation always means causation.

---

# 🔮 Where You'll Use This Later

| Mathematical Concept | ML Application |
|-----------------------|----------------|
| Cartesian Plane | Data Visualization |
| Linear Graph | Linear Regression |
| Scatter Plot | Exploratory Data Analysis (EDA) |
| Curves | Neural Networks |
| Graphs | Model Evaluation |

---

# 🚀 What's Next?

➡️ **Day 11 – Linear Equations**

We'll explore equations of straight lines, understand **slope** and **intercept**, and see how they form the mathematical foundation of **Linear Regression**.

---

# 📚 References

- Mathematics for Machine Learning — Marc Peter Deisenroth, A. Aldo Faisal & Cheng Soon Ong
- Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow — Aurélien Géron
- Matplotlib Documentation

---

> *"Graphs allow us to see relationships that are hidden inside numbers. In Machine Learning, visualization is often the first step toward understanding data."*
