#Education #OCR #Psychology #ResearchMethods

If math is your worst subject, use this guide to translate "Stats Speak" into plain English.

---

## The Big Four Symbols

| Symbol | **What it means** | **Simple Example** |
| :--- | :--- | :--- |
| **$n$** | **Sample Size**: The number of people in the study. | $n=10$ means 10 people were tested. |
| **$N$** | **Final Sample**: Used after removing "tie" scores in tests like the Sign Test. | If 2 people tie, $n=10$ becomes $N=8$. |
| **$\Sigma$** | **Sigma**: Just means "Add them all up." | $\Sigma(2, 4, 6) = 12$. |
| **$p$** | **Probability**: The chance that the result was just a fluke. | $p \leq 0.05$ means less than a 5% chance of a fluke. |

---

## Understanding Statistical Significance
In psychology, we usually look for **$p \leq 0.05$**.
- Think of it like this: If you ran the study 100 times, you would expect to get these results by luck only **5 times** or fewer.
- If $p$ is larger than 0.05 (e.g., $p=0.50$), your result is **not significant** (it was probably a fluke).

---

## Critical vs Observed: The Rule of "S"
You will always have two numbers: one you calculate (**Observed**) and one from a table (**Critical**).

| Rule | **When to use it** | **Which tests?** |
| :--- | :--- | :--- |
| **Observed $\leq$ Critical** | The calculated number must be **smaller** than the table. | **S**ign Test, **M**ann-Whitney **U**, **W**ilcoxon **T**. |
| **Observed $\geq$ Critical** | The calculated number must be **larger** than the table. | **S**pearman's Rho, **C**hi-Square. |

> ** Beginner Hack**: All tests with an "**S**" in their name (Sign, Spearman) use the **$\geq$** rule, **EXCEPT** the Sign Test itself.
> (Wait, that's confusing!) 
> **Better Hack**: Just remember **"Smaller for S, M, W"** (Sign, Mann, Wilcoxon) and **"Bigger for the rest."**

---

## Degrees of Freedom ($df$)
This sounds scary but it's just a number you use to find the right row in a table (like Chi-Square).
- **In Chi-Square**: $(Rows - 1) \times (Columns - 1)$.
- If you have a 2x2 table, your $df$ is always **1**.

---

## OCR Exam Vocabulary

- **Calculated Value**: Same as "Observed Value."
- **One-Tailed**: Use this column if your hypothesis is **Directional** (says one group will be *better*).
- **Two-Tailed**: Use this column if your hypothesis is **Non-Directional** (says there will be a *difference* but doesn't say who's better).
