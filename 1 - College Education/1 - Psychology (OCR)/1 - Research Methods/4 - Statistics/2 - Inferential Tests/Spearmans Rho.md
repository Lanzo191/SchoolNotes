#Education #OCR #Psychology #ResearchMethods

**Spearman's Rho ($r_s$)** is used to find a **correlation** (relationship) between two variables when you have **Ordinal Data** (ranked data).

---

##  The "Math-Free" Explanation
Imagine you want to see if your **rank** in a race (1st, 2nd, 3rd) matches your **rank** in an exam.
- If the 1st place runner also got the 1st highest exam score, there is a perfect match!
- Spearman's Rho looks at the **difference** between these ranks.
- The smaller the total difference, the stronger the relationship!

---

## The Formula Symbols (Simplified)

| Symbol | **What it means in plain English** |
| :--- | :--- |
| **$r_s$** | The final "Rho" score (will be between -1.0 and +1.0). |
| **$d$** | **Difference**: The difference between a participant's two ranks. |
| **$d^2$** | **Difference Squared**: The difference multiplied by itself (removes negatives). |
| **$\Sigma$** | **Sigma**: "Add them all up" at the end. |
| **$n$** | The number of participants in your sample. |

---

## Step-by-Step Calculation (Simplified)

| Step | **What to do** | **Math Version** |
| :--- | :--- | :--- |
| **1.** | Rank both sets of scores (from 1st upwards). | Rank A, Rank B |
| **2.** | Subtract Rank B from Rank A for each person. | $(Rank A - Rank B)$ or **$d$** |
| **3.** | Square each result (multiply by itself). | **$d^2$** |
| **4.** | **Add up** all the $d^2$ numbers. | **$\Sigma d^2$** |
| **5.** | Use the Spearman's Rho formula (given in exam). | $r_s$ formula |

---

## What the Score Means

| Rho Value | **Strength** | **Direction** |
| :--- | :--- | :--- |
| **+1.0** | Perfect | **Positive** (Both go up together) |
| **-1.0** | Perfect | **Negative** (One goes up, one goes down) |
| **0.0** | None | No relationship at all. |

---

##  Worked Example: Revision & Results
**Hypothesis**: There is a positive relationship between hours spent revising and exam scores (One-tailed).

| Student | Hours Rev (Rank) | Exam Score (Rank) | **$d$ (Diff)** | **$d^2$** |
| :--- | :--- | :--- | :--- | :--- |
| **A** | 10 (**3**) | 80 (**3**) | 0 | **0** |
| **B** | 5 (**1**) | 60 (**1**) | 0 | **0** |
| **C** | 15 (**4**) | 90 (**4**) | 0 | **0** |
| **D** | 8 (**2**) | 70 (**2**) | 0 | **0** |

### Step-by-Step Calculation:
1.  **Rank both**: Notice how both ranks match perfectly (1st for 1st, 2nd for 2nd).
2.  **Calculate $d$**: Subtract ranks ($3-3, 1-1, 4-4, 2-2$). All differences are 0.
3.  **Sum of $d^2$**: $\Sigma d^2 = \mathbf{0}$.
4.  **Formula result**: $r_s = \mathbf{+1.0}$.
5.  **Critical Value**: For $N=4$ at 0.05, the Critical Value is **1.0**.
6.  **Conclusion**: Is $r_s \geq$ CV? Is $1.0 \geq 1.0$? **Yes.**
    *   *Result*: Significant positive correlation.

---

## Evaluation (Strengths & Weaknesses)

| Strength | Weakness |
| :--- | :--- |
| **Good for Rankings**: Perfect for data like "1st, 2nd, 3rd" or Likert Scales (1-5). | **Correlation only**: It *never* proves that one thing caused the other. |
| **Clear Score**: Gives you a single number that is easy to understand. | **Outliers**: One weird result can mess up the whole correlation. |

---

## OCR Exam Tip: Significance
For Spearman's Rho, your calculated number ($r_s$) must be **GREATER THAN OR EQUAL TO ($\geq$)** the Critical Value in the table to be significant.
- **Why?**: The closer to 1 (or -1), the stronger the relationship!
- **Mnemonic**: Spearman is a **Super** test, so it needs a **Super big** value!
