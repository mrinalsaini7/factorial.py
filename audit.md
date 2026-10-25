# Python Program Audit Report
## Project: Factorial Calculation Using Python

### 1. Project Information

- **Project Name:** Factorial Calculator
- **Programming Language:** Python
- **Program Type:** Basic Loop-Based Program
- **Objective:** To calculate the factorial of a given number using a `for` loop.

### 2. Source Code

```python
n = 5
fact = 1

for i in range(1, n + 1):
    fact = fact * i

print(fact)
```

### 3. Audit Objective

The purpose of this audit is to examine the correctness, logic, efficiency, and reliability of the Python program used to calculate the factorial of a number.

### 4. Code Review

| Audit Parameter | Observation |
|---|---|
| Syntax | Correct |
| Logic | Correct for the given input |
| Variable Initialization | Correct |
| Loop Condition | Correct |
| Output | Correct |
| Time Complexity | O(n) |
| Space Complexity | O(1) |
| External Libraries | Not required |

### 5. Algorithm Verification

1. Initialize `n = 5`.
2. Initialize `fact = 1`.
3. Start the loop from `i = 1` to `i = 5`.
4. Multiply `fact` by the current value of `i`.
5. Repeat until the loop finishes.
6. Print the final value of `fact`.

### 6. Test Case

| Test Parameter | Expected Result | Actual Result | Status |
|---|---:|---:|---|
| Input: `n = 5` | 120 | 120 | PASS |

### 7. Execution Trace

| Iteration (`i`) | Calculation | `fact` |
|---:|---|---:|
| 1 | 1 × 1 | 1 |
| 2 | 1 × 2 | 2 |
| 3 | 2 × 3 | 6 |
| 4 | 6 × 4 | 24 |
| 5 | 24 × 5 | 120 |

**Final Output:**
```text
120
```

### 8. Findings and Recommendations

**Findings:**
- The program correctly calculates the factorial of 5.
- The loop executes the required number of iterations.
- The program uses minimal memory and requires no external dependencies.

**Recommendations:**
- Accept input dynamically instead of hardcoding `n = 5`.
- Validate that the input is a non-negative integer.
- Test additional values, including `0` and `1`.
- Add error handling for invalid inputs.

### 9. Audit Conclusion

The program has been reviewed and found to be logically correct for the specified input of `n = 5`. It produces the expected output of `120` and has a time complexity of O(n) and an auxiliary space complexity of O(1).

**Overall Audit Status: PASS — for the tested input.**
