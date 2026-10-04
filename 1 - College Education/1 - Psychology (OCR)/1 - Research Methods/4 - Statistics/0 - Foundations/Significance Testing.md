#Psychology #ResearchMethods #Statistics #OCR  

Significance testing is a statistical method used in psychology to determine whether research findings are likely to be due to chance or represent a real effect.


# Choosing a Statistical Test 

This guide summarises when to use each statistical test based on:
- **Level of measurement**  
- **Experimental design**  
- **Type of relationship/difference being tested**  

## Levels of Measurement
- **[[Nominal Data]]**: Categories (e.g., helped vs. didn’t help).  
- **[[Ordinal Data]]**: Ranked data or subjective scales (e.g., rating from 1–10).  
- **Interval/[[Ratio Data]]**: Numerical data with equal intervals (e.g., reaction time in ms).

## Parametric vs Non-Parametric
- OCR Psychology uses *mostly non-parametric* tests.  
- Parametric tests assume the data is normally distributed, measured on interval/ratio scales, and have equal variances.  
- Parametric tests are almost never required unless explicitly taught (e.g., t-tests).  
- Non-parametric tests do **not** assume normal distribution and are suitable for [[Ordinal Data]] or skewed [[Interval Data]].

---

# Statistical Tests Summary

## 1. Chi-Squared Test (χ²)
**Use when:**  
- You have **nominal data**.  
- You are looking for a **difference** or an **association**.  
- The design is **independent groups**.  
- Data is in **frequencies**.  

**Example:** Is there a difference in helping behaviour between males and females?

---

## 2. Mann–Whitney U Test
**Use when:**  
- You have **ordinal** or **interval** data.  
- You are testing for a **difference**.  
- **Independent groups design** (two separate groups).  

**Example:** Do males and females differ in stress rating?

---

## 3. Wilcoxon Signed-Rank Test
**Use when:**  
- You have **ordinal** or **interval** data.  
- You are testing for a **difference**.  
- **Repeated measures** or **matched pairs** design.  

Participants complete a memory test **before and after caffeine**. Scores out of 10:

| Participant | Before | After |
|-------------|--------|-------|
| 1           | 6      | 7     |
| 2           | 5      | 5     |
| 3           | 7      | 6     |
| 4           | 4      | 6     |
| 5           | 6      | 8     |

### Step 1: Calculate Differences (After - Before)

| Participant | Before | After | Difference |
|-------------|--------|-------|------------|
| 1           | 6      | 7     | +1         |
| 2           | 5      | 5     | 0          |
| 3           | 7      | 6     | -1         |
| 4           | 4      | 6     | +2         |
| 5           | 6      | 8     | +2         |

> Ignore zero differences (Participant 2).

### Step 2: Rank the Absolute Differences
| Participant | Difference | Rank |
| ----------- | ---------- | ---- |
| 1           | +1         | 1    |
| 3           | -1         | 1    |
| 4           | +2         | 3.5  |
| 5           | +2         | 3.5  |

>  **Footnote:** When two or more differences have the same absolute value (ties), assign them the **average of the ranks** they would occupy. For example, if the tied values would have ranks 3 and 4, each receives (3+4)/2 = 3.5.


### Step 3: Assign Signs to Ranks

| Participant | Difference | Rank |
| ----------- | ---------- | ---- |
| 1           | +1         | 1    |
| 3           | -1         | 1    |
| 4           | +2         | 3.5  |
| 5           | +2         | 3.5  |

### Step 4: Sum Positive and Negative Ranks
After ranking the absolute differences and assigning signs:

| Participant | Signed Rank |
|-------------|-------------|
| 1           | +1          |
| 3           | -1          |
| 4           | +3.5        |
| 5           | +3.5        |

- Add all the **positive ranks** → **T+ = 1 + 3.5 + 3.5 = 8**  
- Add all the **negative ranks** → **T- = 1**  



### Step 5: Find the Test Statistic (T)
- **T** is always the **smaller of the two sums** (T+ and T-)  
- Here: smaller of 8 (T+) and 1 (T-) → **T = 1**  

Wilcoxon test looks at the **least amount of change in one direction** to see if it’s still unusual.  

### Step 6: Compare T to the Critical Value
- **Critical value** (Tcrit) is a number from a Wilcoxon table that tells you what counts as “unusual enough” for your sample size (n) and significance level (α, usually 0.05)  
- For n = 4 non-zero differences and two-tailed α = 0.05 → Tcrit = 0  
- Compare your T:  
  - **If T ≤ Tcrit → difference is significant → reject null hypothesis**  
  - **If T > Tcrit → difference is not significant → fail to reject null hypothesis**  

**Example:**  
- Calculated T = 1, Tcrit = 0 → 1 > 0 → **Not significant**  

### Simple Analogy
- Imagine T+ and T- are **two piles of points** from your data.  
- The smaller pile is your T.  
- The critical value is like a **line on the floor**: if your pile reaches the line or goes below, it’s unusual enough to matter.  
- If it doesn’t reach the line, the differences could just happen by chance.


### Interpretation
- There is **no statistically significant difference** in memory scores before and after

![[Pasted image 20251114121033.png]]

---

## 4. Spearman’s Rho (ρ)
**Use when:**  
- You have **ordinal** or **interval** data.  
- You want to test for a **correlation** (relationship).  

**Example:** Is there a relationship between hours revised and exam score?

---

# Quick Test-Choice Table

| Research Aim | Data Type | Design | Test |
|--------------|-----------|--------|------|
| Difference | Nominal | Independent groups | Chi-Squared |
| Difference | Ordinal/Interval | Independent groups | Mann–Whitney U |
| Difference | Ordinal/Interval | Repeated measures | Wilcoxon |
| Correlation | Ordinal/Interval | N/A | Spearman’s Rho |

---

## Significance
- Compare your test statistic (U, T, χ², or ρ) to a **critical value table**.  
- Use **p = 0.05** unless told otherwise.  
- Consider **one-tailed vs two-tailed** hypothesis based on prediction.

---- 
# Examples 

"A Study to investigate the hypothesis that people perform worse on an arithmetic test out of 20 after drinking 4 pints of beer then people who haven't drunk. Participants are tested first with beer then without "

- One tailed test / Repeated Measure 
- [[Interval Data]]
- Wilcoxon (Related T Test)

Why Not the Others?
- **Mann–Whitney U:** independent groups only → not suitable.  
- **Chi-Squared:** [[Nominal Data]] only → not applicable.  
- **Spearman's Rho:** tests correlation → not a relationship study.


"A Study investigating levels of stress (1-10) and driving ability on a similar scale "

- Independent Measure 
- [[Ordinal Data]]
- Spearman's Rho 

"A study to test the hypothesis that there are sex differences between short term memory span of 12 year old girls and boys when there was a list of 20 words of equal difficulty"

- Independent Measure 
- [[Interval Data]] 
- Wilcoxon (Unrelated T Test)

"A study to see if introverts or extroverts go to a party, you have a sample of both and ask them whether they went to a party on this evening"

- Independent Measure 
- [[Nominal Data]]
- Chi-Squared 