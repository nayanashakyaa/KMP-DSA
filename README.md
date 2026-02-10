# KMP Algorithm Visualizer

A Python-based graphical tool designed to demonstrate the **Knuth–Morris–Pratt (KMP)** string-matching algorithm. This project visualizes character-by-character comparisons and the efficiency of the Longest Prefix Suffix (LPS) array in real-time.

## 📌 Project Overview

The KMP algorithm optimizes string searching by avoiding redundant comparisons. This visualizer provides an intuitive look at how the algorithm "skips" through the text based on pre-processed pattern data.

### Key Features

* **Real-Time Animation:** Visualizes the sliding window approach and character matches using Matplotlib.
* **Dynamic Input:** Support for user-defined text sequences and search motifs.
* **Efficiency:** Demonstrates  time complexity in action.
* **Academic Implementation:** Incorporates fundamental data structures (Stacks, Queues, and Linked Lists) to manage state and match results.

## 🧠 Algorithm & Complexity

The core of this tool is the Knuth–Morris–Pratt logic, which utilizes an auxiliary **LPS (Longest Prefix Suffix)** array to determine the next shift.

| Metric | Complexity |
| --- | --- |
| **Time Complexity** |  |
| **Space Complexity** |  |
| **Visualization Delay** | 700ms (Step-by-step) |

---

## 🛠️ Technologies Used

* **Python:** Core Logic
* **Tkinter:** GUI for user input and error handling
* **Matplotlib:** Dynamic plotting and visualization

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed. You will need the `matplotlib` library:

```bash
pip install matplotlib

```

### Installation & Execution

1. Clone this repository:
```bash
git clone https://github.com/your-username/KMP-Visualization.git

```


2. Navigate to the directory:
```bash
cd KMP-Visualization

```


3. Run the application:
```bash
python kmp.py

```



---

## 🖥️ How It Works

1. **Input:** Enter the main **Text** and the **Pattern** you wish to find in the GUI.
2. **Preprocessing:** The program calculates the LPS array for the pattern.
3. **Visualization:** * **Text (Black):** The target sequence.
* **Pattern (Blue):** The sliding motif being compared.
* **Status (Green):** Displays the exact position when a match is successfully identified.



---

## 📚 Educational Context

This project was developed for **Data Structures & Algorithms (DSA)** study, focusing on:

* Pattern matching optimization.
* Practical application of auxiliary arrays.
* GUI development for algorithm demonstration.

**Submitted by:** Prapti Poudel & Nayana Shakya


