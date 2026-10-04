#Education #OCR #Psychology #ResearchMethods

In the exam, you will often be given a table of **Critical Values**. You must know how to pick the right number from that table to see if your result is significant.

## Step 1: Identify your Hypothesis Type
- **One-Tailed**: Use this if your hypothesis was **Directional** (e.g., "Men will score *higher* than women").
- **Two-Tailed**: Use this if your hypothesis was **Non-Directional** (e.g., "There will be a *difference* between men and women").
- *The table will usually have two different rows/columns for these.*

## Step 2: Identify the Significance Level
- Always look for **0.05 (5%)** unless the question explicitly tells you a different one (like 0.01).

## Step 3: Find your Degrees of Freedom ($df$) or Sample Size ($N$)
Each test uses a different way to find the right row:
- **[[Sign Test]]**: Use **$N$** (number of participants after excluding zeroes).
- **Wilcoxon**: Use **$N$** (number of non-zero differences).
- **Mann-Whitney**: Use **$n_1$** and **$n_2$** (the size of both groups).
- **Spearman / Pearson**: Use **$N$** or **$df$ ($N-2$)**.
- **[[Chi-Square]]**: Use **$df$**.
- **t-tests**: Use **$df$**.

## Step 4: Find the Intersection
Find where your row ($N$ or $df$) meets your column (one/two-tailed at 0.05). That number is your **Critical Value**.

---

## The Comparison Step
Once you have the Critical Value:
1. **The "S" Rule**: If the test has an "S" in it (**Sign, Mann-Whitney, Wilcoxon, Spearman**), your observed value must be **$\leq$** the critical value.
2. **The Others**: For **Chi-Square, t-tests, Pearson**, your observed value must be **$\geq$** the critical value.

---