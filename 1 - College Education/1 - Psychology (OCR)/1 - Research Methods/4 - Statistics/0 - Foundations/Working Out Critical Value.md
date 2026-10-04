#Psychology #OCR #Statistics #CriticalValues #ResearchMethods

## What Is a Critical Value?
The critical value is the number you look up in a statistics table.  
You compare **your calculated test value** (T, U, χ², or ρ) to this number to decide if your result is significant.

## What Do I Actually Do?
1. Choose the correct statistical test.  
2. Work out **N** (sample size) for that test.  
3. Look up the **critical value** at p = 0.05 (one- or two-tailed depending on the hypothesis).  
4. Compare your test statistic to the table value using the rules below.

---

## Rules for Each Test

### Wilcoxon Signed-Rank Test  
**Used for:** Repeated measures, ordinal/interval data.  
- Your test statistic = **the smaller of T⁺ and T⁻**.  
- If **T ≤ critical value**, the result is significant.

### Mann–Whitney U Test  
**Used for:** Independent groups, ordinal/interval data.  
- Your test statistic = **your calculated U value** (choose the smaller U if you calculated both).  
- If **U ≤ critical value**, the result is significant.

### Chi-Squared Test  
**Used for:** Nominal data, independent groups.  
- Your test statistic = χ² that you calculated.  
- If **χ² ≥ critical value**, the result is significant.  
(Notice this one is the opposite - bigger = significant.)

### Spearman’s Rho  
**Used for:** Correlation, ordinal/interval data.  
- Your test statistic = your correlation coefficient (ρ).  
- If **|ρ| ≥ critical value**, the result is significant.

---

## How to Find N (Sample Size)
- **Wilcoxon:** N = number of non-zero differences.  
- **Mann–Whitney:** N₁ = size of group 1, N₂ = size of group 2.  
- **Chi-Squared:** Based on degrees of freedom = (rows − 1)(columns − 1).  
- **Spearman:** N = number of paired scores.

---

## One-Tailed vs Two-Tailed
- Use **one-tailed** if your hypothesis predicts a direction (e.g., “faster”, “higher”, “more”).  
- Use **two-tailed** if your hypothesis just predicts a difference but not which way.

Tables have different critical values for each - make sure you choose the correct column.

---

## Ultra-Short Version

- **Wilcoxon:** smaller T; significant if T ≤ critical value  
- **Mann–Whitney:** smaller U; significant if U ≤ critical value  
- **Chi-Squared:** χ²; significant if χ² ≥ critical value  
- **Spearman:** ρ; significant if |ρ| ≥ critical value  
- **p = 0.05** unless told otherwise  
- **Use table matching N and one/two tailed**
