# Day 2 – Types of Data & Mathematical Thinking

> *"Before building intelligent systems, we must first understand the language of data."*

---

# 🎯 Learning Objective

By the end of this chapter, you will understand:

- What data is.
- Different types of data.
- How computers represent data mathematically.
- Why understanding data is the first step in Machine Learning.

---

# 🤔 What is Data?

Data is a collection of facts, observations, or measurements that can be analyzed to extract useful information.

Machine Learning algorithms **learn from data** rather than being explicitly programmed.

Without data, Machine Learning cannot exist.

Examples of data:

- Student marks
- House prices
- Weather information
- Images
- Videos
- Text documents
- Audio recordings

---

# 📊 Information vs Data

People often use these terms interchangeably, but they are different.

| Data | Information |
|------|-------------|
| Raw facts | Processed and meaningful data |
| Individual values | Insights obtained after analysis |
| Input for ML | Output after processing |

### Example

Data:

```text
72, 80, 65, 90, 88
```

Information:

> The average score of the class is 79.

Machine Learning transforms raw data into useful information.

---

# 🗂 Types of Data

## 1️⃣ Numerical Data

Numerical data consists of numbers.

Examples:

- Age
- Height
- Weight
- Temperature
- Salary

Example:

```text
21
45
98.6
₹50,000
```

Machine Learning uses numerical data for calculations and predictions.

---

## 2️⃣ Categorical Data

Categorical data represents labels or groups.

Examples:

- Male / Female
- Red / Blue / Green
- Yes / No
- Country names

Example:

```text
India
USA
Germany
```

Before training a model, categorical data is usually converted into numbers using encoding techniques.

---

## 3️⃣ Structured Data

Structured data is organized into rows and columns.

Example:

| Name | Age | Salary |
|------|-----|--------|
| Alice | 25 | 50000 |
| Bob | 30 | 62000 |

Structured data is commonly stored in databases and spreadsheets.

---

## 4️⃣ Unstructured Data

Unstructured data has no fixed format.

Examples:

- Images
- Videos
- Emails
- Social media posts
- Audio files

Most real-world Machine Learning applications work with unstructured data.

---

# 🧮 How Computers Understand Data

Humans understand words and pictures.

Computers understand **numbers**.

Therefore, every type of data must eventually be represented numerically.

Example:

Image → Matrix of pixel values

Text → Numerical embeddings

Audio → Waveform values

This is why mathematics is fundamental to Machine Learning.

---

# 🤖 Mathematical Thinking in ML

Machine Learning views data mathematically.

For example:

Student marks

```text
70
82
90
76
88
```

Mathematically, this becomes a **vector**.

Later in this course, you'll learn that datasets are represented as **matrices** and transformed using **Linear Algebra**.

---

# 🌍 Real-World Example

Imagine a house price prediction model.

Input data:

| Area | Bedrooms | Age |
|------|----------|-----|
| 1200 | 2 | 5 |
| 1800 | 3 | 2 |
| 2500 | 4 | 1 |

The model learns the relationship between these numerical values and the final house price.

Everything starts with representing the data mathematically.

---

# 💡 Why This Matters in Machine Learning

Every Machine Learning algorithm starts with data.

Examples:

- Spam Detection → Emails
- Face Recognition → Images
- Speech Recognition → Audio
- Recommendation Systems → User activity
- Chatbots → Text

Regardless of the application, the first step is always converting data into mathematical representations.

---

# 📌 Did You Know?

Over **90% of the world's data** is unstructured, including images, videos, documents, and social media posts.

Modern AI models like ChatGPT and computer vision systems are designed to learn from this type of data.

---

# 🎓 Interview Insight

Interviewers may ask:

- What is structured and unstructured data?
- Why must categorical data be encoded?
- Why is data preprocessing necessary?

Understanding data types is one of the first concepts expected from every Data Scientist and ML Engineer.

---

# 📖 Summary

Today we learned:

- Data is the foundation of Machine Learning.
- Data can be numerical, categorical, structured, or unstructured.
- Computers understand numbers, not words or images.
- Every Machine Learning problem begins by converting data into mathematical representations.

---

# 🚀 What's Next?

➡️ **Day 3 – Number Systems**

We'll explore how computers represent numbers internally and why binary numbers are important in AI and computing.

---

# 📚 References

- Mathematics for Machine Learning — Marc Peter Deisenroth, A. Aldo Faisal & Cheng Soon Ong
- Introduction to Data Science concepts
- Python documentation (NumPy & Pandas)

---

> *"Good models start with good data, but great models start with understanding the data."* 🚀
