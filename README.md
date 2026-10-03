# 🧬 Find Purines and Pyrimidines Using Python

A beginner-friendly **bioinformatics project in Python** that analyzes a DNA sequence by identifying and quantifying its **purine and pyrimidine nucleotides**.

The program counts the four DNA bases and calculates the percentage of purines and pyrimidines, providing a simple introduction to **DNA sequence composition analysis**.

## 🔬 Project Overview

DNA contains four major nitrogenous bases:

| Base             | Type       |
| ---------------- | ---------- |
| **A — Adenine**  | Purine     |
| **G — Guanine**  | Purine     |
| **C — Cytosine** | Pyrimidine |
| **T — Thymine**  | Pyrimidine |

Purines consist of **Adenine (A)** and **Guanine (G)**, while pyrimidines consist of **Cytosine (C)** and **Thymine (T)**.

This project uses Python to automatically count these nucleotide categories and calculate their relative proportions.

## 🎯 Objectives

* Analyze a DNA nucleotide sequence
* Count **purines (A + G)**
* Count **pyrimidines (C + T)**
* Calculate purine percentage
* Calculate pyrimidine percentage
* Practice basic DNA sequence analysis using Python

## 🧬 Analysis Workflow

```text
DNA Sequence
     ↓
Validate / Process Sequence
     ↓
Count A + G
     ↓
Purine Count
     ↓
Count C + T
     ↓
Pyrimidine Count
     ↓
Calculate Percentages
     ↓
Sequence Composition Summary
```

## 💻 Technologies

* **Python 3**
* String manipulation
* Conditional logic
* Built-in `count()` function
* Basic bioinformatics concepts

No external Python libraries are required.

## 📁 Repository Structure

```text
Find-Purines-and-Pyrimidines-using-python/
│
├── code.py
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Bioinformatician-dev/Find-Purines-and-Pyrimidines-using-python.git
```

### 2. Navigate to the project

```bash
cd Find-Purines-and-Pyrimidines-using-python
```

### 3. Run the program

```bash
python code.py
```

## 🧪 Example

### Input

```text
ATGCGATACGTTAGC
```

The program analyzes the sequence and separates the nucleotides into:

```text
Purines:
A + G

Pyrimidines:
C + T
```

It then calculates:

```text
Purine Percentage
= (Number of Purines / Total Sequence Length) × 100

Pyrimidine Percentage
= (Number of Pyrimidines / Total Sequence Length) × 100
```

Because every standard DNA nucleotide belongs to one of these two categories, the two percentages should sum to approximately **100%** for a valid DNA sequence.

## 📊 What the Program Calculates

### Purines

```text
A + G
```

### Pyrimidines

```text
C + T
```

### Purine Percentage

```text
Purines / Total Nucleotides × 100
```

### Pyrimidine Percentage

```text
Pyrimidines / Total Nucleotides × 100
```

## 🧠 Bioinformatics Concepts

This project introduces several fundamental concepts used in computational biology:

* DNA sequence representation
* Nucleotide composition
* Sequence statistics
* Purine/pyrimidine classification
* Percentage calculations
* Programmatic biological data analysis

It provides a foundation for more advanced sequence analyses such as **GC-content calculation, motif analysis, sequence comparison, and mutation analysis**.

## 🔮 Future Improvements

Possible extensions include:

* [ ] Add DNA sequence validation
* [ ] Handle lowercase sequences automatically
* [ ] Report individual A, C, G, and T frequencies
* [ ] Calculate GC content
* [ ] Calculate AT content
* [ ] Support FASTA input
* [ ] Analyze multiple sequences
* [ ] Export results to CSV
* [ ] Generate nucleotide-composition plots
* [ ] Add a command-line interface
* [ ] Build a Streamlit web application
* [ ] Add automated unit tests

## 📚 Learning Outcomes

By completing this project, you can practice:

* Working with biological sequences in Python
* Using string operations for sequence analysis
* Applying basic mathematical calculations to biological data
* Translating a biological concept into a computational workflow
* Building small, reproducible bioinformatics utilities

## 👩‍💻 Author

**Bioinformatician-dev**

Bioinformatics • Computational Biology • Genomics • Python • Data Analysis

🔗 GitHub:
https://github.com/Bioinformatician-dev

---

⭐ If you find this project useful for learning Python and bioinformatics, consider starring the repository.

**Discover • Code • Analyze 🧬**
