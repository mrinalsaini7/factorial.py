# Factorial Calculator in Python

## 📌 Overview
This project demonstrates how to calculate the factorial of a number using Python. It uses a `for` loop to multiply all positive integers from `1` to the given number.

## 🎯 Objective
To understand the basic concepts of Python programming, including:
- Variables and initialization
- `for` loops
- Arithmetic operations
- Displaying output using `print()`

## 💻 Source Code

```python
n = 5
fact = 1

for i in range(1, n + 1):
    fact = fact * i

print(fact)
```

## ⚙️ How It Works

1. **Initialize the number:** Set `n = 5`.
2. **Initialize the factorial:** Set `fact = 1`.
3. **Run the loop:** The `for` loop iterates from `1` to `5`.
4. **Calculate the factorial:** Multiply `fact` by each value of `i`.
5. **Display the result:** Print the final factorial.

### Example Calculation

The factorial of 5 is:

`5! = 5 × 4 × 3 × 2 × 1 = 120`

## 📤 Output

```text
120
```

## 🛠️ Requirements
- Python 3.x
- Any Python editor, such as VS Code, PyCharm, or Google Colab

No external libraries are required.

## ▶️ How to Run

1. Clone or download this repository.
2. Save the code in a file named `factorial.py`.
3. Open a terminal in the project directory.
4. Run the following command:

```bash
python factorial.py
```

Alternatively, execute the code directly in Google Colab.

## ⏱️ Complexity Analysis

- **Time Complexity:** `O(n)` — the loop runs `n` times.
- **Space Complexity:** `O(1)` — the program uses a constant amount of additional memory.

## 🚀 Future Improvements
- Accept input from the user.
- Handle negative numbers and invalid inputs.
- Calculate factorials of larger numbers.

## 📚 Concepts Covered
Python basics, loops, variables, multiplication, factorials, and complexity analysis.

## 👨‍💻 Author
Created as a beginner-friendly Python programming exercise.

---

⭐ If you found this project useful, consider giving the repository a star.

