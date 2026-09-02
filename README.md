# Stack Overflow AI Usage Analysis

## 📌 Project Overview

This project analyzes data from the **Stack Overflow Developer Survey** to investigate developers' AI usage, interest, and trust.

### Research Questions

1. How does AI usage differ between **less-experienced and experienced developers**?
2. How are different AI use cases related to **user interest and trust**?

---

## 📂 Dataset

The project uses two datasets:

* **schema** — contains the survey questions.
* **Result** — contains users' responses.

Some survey questions are multiple-choice, so a single question may be represented by multiple columns.

---

## 🔑 Main Variables


AISelect	Represents the user's current AI usage or plans to use AI

AISent	Represents the user's level of interest and sentiment toward AI

AIBen	Represents the user's level of trust in AI

AItoolCurrentlyUsing	Represents the different ways users currently use AI

AISelect

This variable contains three main categories:

* `Yes`
* `No, but i plan to soon`
* `No, and i don't plan too`

The distribution of this variable was analyzed first to understand the overall AI adoption among users.

---

## 🔬 Analysis

### 1. AI Usage Distribution

The distribution of `AISelect` was analyzed to understand overall AI adoption.

### 2. AI Usage & Interest

A **Crosstab** and **Heatmap** were created for:

`AISelect × AISent`

to examine the relationship between AI usage and interest.

### 3. AI Usage & Trust

A **Crosstab** and **Heatmap** were created for:

`AISelect × AIBen`

to examine the relationship between AI usage and trust.


### 4. AI Use Cases

The `AItoolCurrentlyUsing` column contains the different ways users currently use AI, such as coding and other activities.

For each use case:

* The percentage of interested users was calculated using `AISent`.
* The percentage of users who trust AI was calculated using `AIBen`.

This helps identify which AI use cases are associated with higher levels of **interest and trust**.



### 5. Experience Comparison

Less-experienced and experienced developers are compared based on:

* AI usage
* AI interest
* AI trust
* AI use cases

---

## 📊 Visualizations

* AISelect Distribution
* Crosstab Heatmaps
* Interest by AI Use Case
* Trust by AI Use Case
* Experience Group Comparisons

---

## 🛠️ Tools

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🎯 Goal

The main goal is to understand how **developer experience and AI use cases** are associated with developers' **AI adoption, interest, and trust**.
