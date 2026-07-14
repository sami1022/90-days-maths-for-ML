# Day 3 – Number Systems

> *"Every image, text, sound, and prediction in Machine Learning is ultimately represented using numbers."*

---

# 🎯 Learning Objective

By the end of this chapter, you will understand:

- What a number system is.
- Different types of number systems.
- Why binary numbers are fundamental in computing.
- How Machine Learning represents data numerically.

---

# 🤔 What is a Number System?

A **number system** is a way of representing numbers using a set of symbols and rules.

Humans commonly use the **Decimal Number System (Base 10)**, while computers use the **Binary Number System (Base 2)**.

Every value processed by a computer—whether it's text, an image, or audio—is ultimately represented as numbers.

---

# 🔢 Types of Number Systems

## 1️⃣ Decimal Number System (Base 10)

The decimal system uses **10 digits**:

```text
0 1 2 3 4 5 6 7 8 9
```

Example:

```text
347
```

Place values:

```text
3 × 10² + 4 × 10¹ + 7 × 10⁰
```

This is the number system we use every day.

---

## 2️⃣ Binary Number System (Base 2)

The binary system uses only **two digits**:

```text
0 and 1
```

Example:

```text
101101
```

Place values:

```text
1×2⁵ + 0×2⁴ + 1×2³ + 1×2² + 0×2¹ + 1×2⁰
```

Every computer stores and processes information in binary.

---

## 3️⃣ Octal Number System (Base 8)

Uses digits:

```text
0–7
```

Although less common today, octal is still encountered in certain computing applications.

---

## 4️⃣ Hexadecimal Number System (Base 16)

Uses:

```text
0–9
A–F
```

Example:

```text
2A
```

Hexadecimal is widely used in:

- Computer memory
- Programming
- Color codes

Example:

```text
#FF5733
```

is a hexadecimal color representation.

---

# 💻 Why Do Computers Use Binary?

Electronic circuits have only two stable states:

- ON
- OFF

These are represented as:

```text
1 → ON

0 → OFF
```

Since computers are built using electronic switches (transistors), binary is the most reliable and efficient way to represent information.

---

# 📊 Representing Different Types of Data

Although data appears in different forms, computers convert everything into numbers.

| Data Type | Numerical Representation |
|------------|--------------------------|
| Text | ASCII / Unicode values |
| Images | Pixel values |
| Audio | Waveform samples |
| Videos | Sequence of image frames |
| Categories | Encoded integers |

For example:

Character:

```text
A
```

ASCII Value:

```text
65
```

An image is represented as a matrix of pixel intensities.

A grayscale image might look like:

```text
120 130 128
 95 110 140
210 200 180
```

Machine Learning models work with these numerical values—not the visual image itself.

---

# 🤖 Why Number Systems Matter in Machine Learning

Machine Learning algorithms perform mathematical computations.

Therefore, every input must first be converted into numbers.

Examples:

### Spam Detection

Email text

↓

Numerical vectors

↓

Prediction

---

### Image Classification

Image

↓

Pixel matrix

↓

Neural Network

↓

Prediction

---

### Recommendation Systems

User behavior

↓

Numerical features

↓

Recommendation

---

# 🌍 Real-World Example

When you upload a selfie to unlock your smartphone:

- The camera captures an image.
- The image is converted into pixel values.
- A Machine Learning model processes those numbers.
- The model determines whether the face matches yours.

Although we see a face, the computer only sees numbers.

---

# 📌 Did You Know?

Modern AI models process billions of numerical values every second.

Even a single high-resolution image may contain millions of pixel values that are converted into numbers before being analyzed.

---

# 🎓 Interview Insight

Common interview questions include:

- Why do computers use binary instead of decimal?
- What is the difference between binary and hexadecimal?
- Why must Machine Learning data be converted into numerical values?

Understanding these concepts helps explain how data is represented before any learning begins.

---

# 📖 Summary

Today we learned:

- A number system is a method of representing numbers.
- Computers use the binary number system.
- Images, text, audio, and videos are all converted into numbers.
- Machine Learning algorithms operate only on numerical data.

---

# 🚀 What's Next?

➡️ **Day 4 – Fractions, Decimals & Percentages**

We'll explore how these concepts appear in data preprocessing, probability, and Machine Learning metrics.

---

# 📚 References

- Mathematics for Machine Learning — Marc Peter Deisenroth, A. Aldo Faisal & Cheng Soon Ong
- Computer Architecture Fundamentals
- Digital Logic Basics

---

> *"To a computer, everything is a number. Understanding that is the first step toward understanding Machine Learning."*
