# Mouse vs Trackpad Performance Analysis

## Overview
This project analyzes user performance data collected from a study comparing the use of a mouse versus a trackpad for task completion. The analysis includes:
- Descriptive statistics for performance times.
- A paired t-test to assess statistical significance.
- Visual comparisons using bar graphs with error bars.

The study concludes that there is no significant difference in performance times between the two input devices.

---

## Dataset
- **Source**: Mockaroo
- **Columns**:
  - `User Name`: Identifier for each participant.
  - `Mouse Time`: Task completion time using a mouse (in seconds).
  - `Trackpad Time`: Task completion time using a trackpad (in seconds).
  
Example:
| User Name | Mouse Time | Trackpad Time |
|-----------|------------|---------------|
| User 1    | 2.5        | 3.0           |
| User 2    | 1.8        | 2.5           |

---

## Analysis Steps
### 1. Data Preparation
- Data was entered and cleaned in Microsoft Excel.
- Checked for missing values and ensured consistency in time format.

### 2. Descriptive Statistics
- Calculated:
  - **Mean**: Average time.
  - **Standard Deviation**: Variability of time measurements.
  - **Standard Error**: Uncertainty of the mean.

Example Results:
| Statistic         | Mouse Time | Trackpad Time |
|-------------------|------------|---------------|
| Mean              | 3.43       | 2.97          |
| Standard Deviation| 1.18       | 1.21          |
| Standard Error    | 0.22       | 0.22          |

### 3. Paired t-Test
- Formula: `=T.TEST(Mouse Range, Trackpad Range, 2, 1)`
- **Result**: p-value = 0.1791 (no significant difference).

---

## Visualizations
- Bar graph comparing mean Mouse Time and Trackpad Time.
- Includes error bars to depict variability.

---

## Conclusion
- **Key Findings**: No significant difference in task performance times between the mouse and trackpad.
- **P-value**: 0.1791 > 0.05, supporting the null hypothesis.
  
### Limitations
- Small dataset size may reduce statistical power.
- Individual performance variability was not fully captured.
