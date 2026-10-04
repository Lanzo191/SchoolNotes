#Education #OCR #Psychology #ResearchMethods

The **Sign Test** is a non-parametric test used to find a **difference** when researchers have **[[Nominal Data]]** in a **related design**.

## When to Use
1. **Goal**: Difference.
2. **Design**: Related (Repeated Measures or Matched Pairs).
3. **Data**: Nominal (or data converted to nominal by assigning a "+" or "-" to a change in scores).

---

## Comparison: Binomial vs Sign Test
- A **[[Binomial Test]]** compares a sample against a fixed probability (e.g., "Is 9/10 heads due to chance?").
- The **Sign Test** is a specialized version of the binomial test used to compare two related conditions by looking at the *direction* (sign) of change.

---

## Steps to Calculate the Sign Test

| Step | **Action** |
| :--- | :--- |
| **1. Difference** | For each participant, calculate the difference between their two scores (Condition A - Condition B). |
| **2. Sign** | Assign a **plus (+)** if the score increased, a **minus (-)** if it decreased, and a **zero (0)** if there was no change. |
| **3. Filter** | Count and **remove all zero (0) results**. They are excluded from the analysis. |
| **4. Calculate N** | The final sample size ($N$) is the number of participants left (pluses + minuses). |
| **5. Observed Value (s)** | Count the total pluses and total minuses. The **Observed Value ($s$)** is the **smaller** of these two counts. |
| **6. Critical Value** | Look up the Critical Value for your $N$ at $p \leq 0.05$ (at your one-tailed or two-tailed hypothesis). |
| **7. Compare** | For the Sign Test, the **Observed Value ($s$)** must be **$\leq$ the Critical Value** to be significant. |

---

##  Worked Example: The "Coffee & Memory" Study
**Hypothesis**: Drinking coffee will increase the number of words recalled (One-tailed).

| Participant | No Coffee | Coffee | Difference | **Sign** |
| :--- | :--- | :--- | :--- | :--- |
| **1** | 10 | 15 | +5 | **+** |
| **2** | 12 | 18 | +6 | **+** |
| **3** | 14 | 14 | 0 | **Ignore (0)** |
| **4** | 9 | 12 | +3 | **+** |
| **5** | 15 | 13 | -2 | **-** |
| **6** | 11 | 16 | +5 | **+** |

### Step-by-Step Calculation:
1.  **Count signs**: 4 pluses (+), 1 minus (-).
2.  **$N$**: We started with 6, but Participant 3 had no change. So **$N = 5$**.
3.  **Observed Value ($s$)**: The smaller number of signs is the 1 minus. So **$s = 1$**.
4.  **Critical Value**: For $N=5$ (one-tailed at 0.05), the Critical Value is **0**.
5.  **Conclusion**: Is $s \leq$ CV? Is $1 \leq 0$? **No.** 
    *   *Result*: Not significant. Coffee didn't reliably help memory in this tiny sample.

---

## Evaluation (Strengths & Weaknesses)

| Strength | Weakness |
| :--- | :--- |
| **Simple Calculation**: One of the few statistical tests students may be asked to actually calculate in an exam. | **Loss of Information**: By converting raw scores (interval) into simple signs (+/-), you lose the magnitude of the difference (e.g., an increase of 1 vs 100 is treated the same). |
| **Non-Parametric**: Does not assume a normal distribution in the data. | **Low Sensitivity**: Because it is less "powerful," it is more likely to result in a Type II error (failing to find a significant effect that exists). |

---

## OCR Exam Question Example
> "A researcher found 8 pluses and 2 minuses. The critical value for $N=10$ at $p \leq 0.05$ is 1. Is it significant?"
- **Observed Value ($s$)** = 2 (the smaller number).
- **Critical Value** = 1.
- **Rule**: $s \leq$ CV for significance.
- **Answer**: $2 \leq 1$ is **False**. Therefore, the result is **not significant**.
