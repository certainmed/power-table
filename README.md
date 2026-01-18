# Power Table

> A dynamic exponentiation table for calculating and visualizing $x^n$ values

## 📖 Overview

**Power Table** is an interactive web application that dynamically generates exponentiation tables. It allows users to view the results of $x^n$ calculations in an easy-to-read table format, where:

- **Rows:** Represent the base number ($x$)
- **Columns:** Represent the exponent ($n$)

## ✨ Key Features

### 1. Dynamic Exponentiation Table
Automatically generates a power table based on the user-defined range of base numbers and exponents.

### 2. Multi-Theme Support
The application offers 4 visual themes:

| Theme | Description |
|-------|-------------|
| **Minimalist** | A clean and simple look with neutral colors |
| **Midnight** | An elegant dark mode with night-inspired tones |
| **Nature** | A nature-inspired theme featuring greens and earth tones |
| **Cyber** | A futuristic aesthetic with neon colors and a tech vibe |

### 3. Mathematical Notation
Utilizes LaTeX mathematical notation to render expressions such as $x^n$ and $x \setminus n$ cleanly and accurately.

### 4. Intuitive Interface
- Clear header with title and subtitle
- Easy-to-understand row and column configuration
- Responsive table visualization

## 🔧 How to Use

1. Open the Power Table application
2. Set the range for **Rows (Base Number x)**
3. Set the range for **Columns (Exponent n)**
4. Select a theme based on your visual preference
5. The table will be generated automatically

## 📐 Calculation Logic

Each cell in the table is calculated using the exponentiation formula:

$$\text{Cell Value} = x^n$$

Where:
- $x$ = the base value from the corresponding row
- $n$ = the exponent value from the corresponding column

### Example Output

|  $x \setminus n$  |  1  |  2  |  3  |  4  |
|:-----------------:|:---:|:---:|:---:|:---:|
| **2** | 2 | 4 | 8 | 16 |
| **3** | 3 | 9 | 27 | 81 |
| **4** | 4 | 16 | 64 | 256 |

## 🛠️ Technologies

- HTML5
- CSS3 (with a theming system)
- JavaScript (for dynamic calculations)
- LaTeX/MathJax (for rendering mathematical notation)

## 📝 License

This project is open source and free to use for educational purposes.

---

**Power Table** – Visualizing the power of numbers with elegance ⚡
