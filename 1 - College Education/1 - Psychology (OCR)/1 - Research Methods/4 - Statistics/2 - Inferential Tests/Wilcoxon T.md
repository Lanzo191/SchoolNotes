#Education #OCR #Psychology #ResearchMethods

**Wilcoxon T** (also known as the Wilcoxon Signed-Rank Test) is a non-parametric test used to find a **difference** with a **related design** and **[[Ordinal Data]]**.

## When to Use
1. **Goal**: Difference.
2. **Design**: Related (Repeated Measures or Matched Pairs).
3. **Data**: Ordinal (or Interval data not normally distributed).

---

## Steps to Calculate Wilcoxon T

| Step | **Action** |
| :--- | :--- |
| **1. Difference** | Calculate the difference between the two scores for each participant. |
| **2. Rank** | Rank the differences from **smallest to largest**, ignoring whether they are positive or negative (**ignore the sign**). |
| **3. Sign** | Re-apply the plus or minus sign to each rank. |
| **4. Sum** | Add up the positive ranks ($W_+$) and the negative ranks ($W_-$). |
| **5. Observed (T)** | The **Observed Value ($T$)** is the **smaller** of the two sums. |
| **6. Filter** | Zero differences are ignored when ranking and calculating $N$. |
| **7. Compare** | For Wilcoxon T, the **Observed Value ($T$)** must be **$\leq$ the Critical Value** to be significant. |

---

##  Worked Example: 
**Hypothesis**: Attending a workshop will reduce anxiety scores (One-tailed).

| Participant | Before | After | Difference | Rank of Diff | **Sign** |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **A** | 40 | 30 | -10 | **4** | **-** |
| **B** | 45 | 40 | -5 | **2** | **-** |
| **C** | 30 | 22 | -8 | **3** | **-** |
| **D** | 20 | 23 | +3 | **1** | **+** |

### Step-by-Step Calculation:
1.  **List differences**: -10, -5, -8, +3.
2.  **Rank differences (ignoring sign)**: 3 (Rank 1), 5 (Rank 2), 8 (Rank 3), 10 (Rank 4).
3.  **Sum ranks**: 
    - Sum of **Positive** ranks ($W_+$) = **1**.
    - Sum of **Negative** ranks ($W_-$) = $2+3+4 = \mathbf{9}$.
4.  **Observed Value ($T$)**: The smaller sum is **1**. So **$T = 1$**.
5.  **Critical Value**: For $N=4$ (one-tailed at 0.05), the Critical Value is **0**.
6.  **Conclusion**: Is $T \leq$ CV? Is $1 \leq 0$? **No.**
    *   *Result*: Not significant. Anxiety didn't drop enough to be sure it wasn't a fluke.

---

## Evaluation (Strengths & Weaknesses)

| Strength | Weakness |
| :--- | :--- |
| **More Powerful than the Sign Test**: Uses the magnitude of the difference (ranking) rather than just the direction (+/-). | **More Complex**: Ranking differences and handling ties takes more time and is more prone to calculation errors. |
| **Best for Related Data**: Ideal for before-and-after studies where data is a rating scale (Ordinal). | **Non-Parametric**: Still less powerful than a Related t-test because it ignores the actual numerical distance between raw scores. |

---

## Critical Comparison Table

| Feature | **Sign Test** | **Wilcoxon T** |
| :--- | :--- | :--- |
| **Design** | Related (Repeated) | Related (Repeated) |
| **Data Level** | Nominal | Ordinal |
| **Significance Rule** | **Observed $\leq$ Critical** | **Observed $\leq$ Critical** |
| **Calculation** | Direction of change (+/-) | Rank of differences |

---

## OCR Exam Question Example
> "A researcher tests the same group before and after a training course using a score out of 50. Which test?"
- **Answer**: Wilcoxon T.
- **Why?**: The design is **related** (same people) and the data is **ordinal** (score out of 50 is treated as ordinal in OCR if not specified as interval).
