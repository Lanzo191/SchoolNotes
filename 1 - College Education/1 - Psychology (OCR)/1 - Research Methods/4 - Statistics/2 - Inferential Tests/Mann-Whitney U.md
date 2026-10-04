#Education #OCR #Psychology #ResearchMethods

**Mann-Whitney U** is a non-parametric test used to find a **difference** with **independent groups** and **[[Ordinal Data]]**.

## When to Use
1. **Goal**: Difference.
2. **Design**: Independent (Unrelated).
3. **Data**: Ordinal (can also be used for Interval data that is not normally distributed).

---

## Steps to Calculate Mann-Whitney U

| Step | **Action** |
| :--- | :--- |
| **1. Combine** | Place all scores from both groups into one list. |
| **2. Rank** | Rank all scores from **1 (lowest)** upwards. If two scores are the same, give them the average of the ranks they would have taken. |
| **3. Separate** | Separate the ranks back into their original groups (Group 1 and Group 2). |
| **4. Sum** | Add the ranks for each group ($R_1$ and $R_2$). |
| **5. Formula** | Use the formula to find the observed $U_1$ and $U_2$ values. |
| **6. Observed (U)** | The **Observed Value ($U$)** is the **smaller** of the two calculated $U$ values. |
| **7. Compare** | For Mann-Whitney U, the **Observed Value ($U$)** must be **$\leq$ the Critical Value** to be significant. |

---

##  Worked Example: "Introverts vs Extroverts"
**Hypothesis**: There is a difference in the number of words spoken in a 5-minute conversation between introverts and extroverts (Two-tailed).

| Group 1 (Introverts) | Rank | Group 2 (Extroverts) | Rank |
| :--- | :--- | :--- | :--- |
| 100 | **2** | 120 | **4** |
| 110 | **3** | 150 | **6** |
| 80 | **1** | 130 | **5** |

### Step-by-Step Calculation:
1.  **Rank all scores together**: 80 (1), 100 (2), 110 (3), 120 (4), 130 (5), 150 (6).
2.  **Sum the ranks**: 
    - $R_1$ (Introverts) = $2+3+1 = \mathbf{6}$
    - $R_2$ (Extroverts) = $4+6+5 = \mathbf{15}$
3.  **Observed Value ($U$)**: Using the formula, we find two $U$ values (e.g., $U_1=0$ and $U_2=9$).
    - **Observed Value ($U$)** = **0** (always the smaller one).
4.  **Critical Value**: For $n_1=3, n_2=3$ at $p \leq 0.05$, the Critical Value is **0**.
5.  **Conclusion**: Is $U \leq$ CV? Is $0 \leq 0$? **Yes.**
    *   *Result*: Significant! Extroverts speak more than introverts.

---

## Evaluation (Strengths & Weaknesses)

| Strength | Weakness |
| :--- | :--- |
| **More Sensitive than Chi-Square**: Uses ranked data rather than simple counts, providing more information. | **Less Sensitive than t-test**: Does not take into account the exact distance between scores (intervals). |
| **Non-Parametric**: Can be used on skewed data or small sample sizes where a t-test is inappropriate. | **Time-Consuming**: Ranking large numbers of participants by hand is difficult and prone to error. |

---

## Critical Comparison Table

| Feature | **Sign Test** | **Mann-Whitney U** |
| :--- | :--- | :--- |
| **Design** | Related (Repeated) | Independent |
| **Data Level** | Nominal | Ordinal |
| **Significance Rule** | **Observed $\leq$ Critical** | **Observed $\leq$ Critical** |
| **Calculation** | Sign (+/-) | Ranking (1, 2, 3...) |

---

## OCR Exam Question Example
> "A researcher has two separate groups of students. They rate their anxiety from 1-10. Which test is best?"
- **Answer**: Mann-Whitney U.
- **Why?**: The groups are **independent** and the data is **ordinal** (a rating scale).
