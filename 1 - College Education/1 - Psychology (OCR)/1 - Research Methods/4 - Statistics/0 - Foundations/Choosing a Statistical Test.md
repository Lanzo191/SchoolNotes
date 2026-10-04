#Education #OCR #Psychology #ResearchMethods

To choose the correct statistical test, you must identify three things:
1. **The Goal**: Are you looking for a **Difference** or a **Correlation** (Relationship)?
2. **The Design**: Is it **Independent Measures** (unrelated) or **Repeated Measures/Matched Pairs** (related)?
3. **The Data Level**: Is it **Nominal**, **Ordinal**, or **Interval**?

---

## The Decision Table 

| Data Level   | **Difference (Independent design)** | **Difference (Repeated/Matched design)** | **Correlation / Relationship** |
| :----------- | :---------------------------------- | :--------------------------------------- | :----------------------------- |
| **Nominal**  | **[[Chi-Square]]**                  | **[[Sign Test]]**                        | **[[Chi-Square]]**             |
| **Ordinal**  | **[[Mann-Whitney U]]**              | **[[Wilcoxon T]]**                       | **[[Spearmans Rho]]**          |
| **Interval** | **Unrelated t-test**                | **Related t-test**                       | **Pearson’s r**                |

---

## Special Test: The Binomial Test
The **[[Binomial Test]]** is used for **Nominal** data when you have a **single sample** with two categories (e.g., "Pass/Fail") and want to see if the outcome is due to chance (0.5).
- Note: The **Sign Test** is a type of binomial test used for related designs.

---

## Summary of Rules for Significance

| Test | **Requirement for Significance** |
| :--- | :--- |
| **Sign Test** | Observed Value ($s$) **$\leq$** Critical Value |
| **Mann-Whitney U** | Observed Value ($U$) **$\leq$** Critical Value |
| **Wilcoxon T** | Observed Value ($T$) **$\leq$** Critical Value |
| **Spearman's Rho** | Observed Value ($r_s$) **$\geq$** Critical Value |
| **Chi-Square** | Observed Value ($\chi^2$) **$\geq$** Critical Value |

---

## Mnemonic to Remember the Tests
**"Carrots Should be Mashed With Swede Under Roast Potatoes"**
- **C**hi-Square
- **S**ign Test
- **M**ann-Whitney U
- **W**ilcoxon T
- **S**pearman's Rho
- **U**nrelated t-test
- **R**elated t-test
- **P**earson's r

---

## How to Identify Data Level (OCR Cheat Sheet)

- **Nominal**: Categories/Names (e.g., Yes/No, Gender, Pass/Fail).
- **Ordinal**: Ranked data where gaps are not equal (e.g., Likert Scales 1-5, Race positions 1st/2nd/3rd).
- **Interval**: Measurements with equal units (e.g., Time in seconds, IQ score, Temperature, Height in cm).
