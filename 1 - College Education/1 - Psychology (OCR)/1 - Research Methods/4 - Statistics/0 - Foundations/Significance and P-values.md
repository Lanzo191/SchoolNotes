#Education #OCR #Psychology #ResearchMethods

In Psychology, we need to know if our results are **Significant** (real) or just due to **Chance**.

## 1. The P-Value
- **P $\leq$ 0.05**: This is the standard level of significance. It means there is a **5% or less** probability that the results happened by chance.
- **P > 0.05**: The results are not significant; they are likely due to chance.

## 2. Hypotheses
- **Alternative Hypothesis ($H_1$):** Predicts a significant effect/difference.
- **[[Null Hypothesis]] ($H_0$):** Predicts no significant effect/difference; any change is due to chance.

## 3. Observed vs. Critical Values
After doing the math for a test, you get an **Observed Value**. You then compare this to a **Critical Value** found in a statistics table.
- **The "S" Rule**: For any test with an "S" in the name (**[[Sign Test]], Mann-Whitney, Wilcoxon, Spearman's**), the **Observed** value must be **LESS than or EQUAL to** the Critical value to be significant.
- For others ([[Chi-Square]], t-tests, Pearson's), the Observed must be **GREATER than or EQUAL to** the Critical value.

---

## 4. Type I and Type II Errors
- **Type I Error ("False Positive")**: You say the results are significant, but they aren't. (Usually happens if your p-value is too lenient, e.g., p < 0.10).
- **Type II Error ("False Negative")**: You say the results aren't significant, but they actually are. (Usually happens if your p-value is too strict, e.g., p < 0.01).

---

## Expansive Example: Writing the "Significance Statement"
*In an exam, you might be given an Observed value and a Critical value and asked to conclude. Use this template:*

**Scenario**: You did a Mann-Whitney U test. Your **Observed Value ($U$) is 12**. The **Critical Value is 15**.

**Conclusion**:
1. **Compare**: "The observed value of $U=12$ is **less than** the critical value of 15."
2. **State Significance**: "Therefore, the results are **significant** at the $p \leq 0.05$ level."
3. **Hypothesis**: "We **reject the Null Hypothesis** and **accept the Alternative Hypothesis**."
4. **Context**: "There is a significant difference in [insert variable here] between the two groups."

*Note: If it were NOT significant, you would say the observed is greater than the critical, accept the Null, and state that any difference is due to chance.*


---