#Education #OCR #Psychology #ResearchMethods

The **Binomial Test** is a non-parametric test used for **[[Nominal Data]]** that has exactly two categories (e.g., "Yes/No", "Success/Failure", "Heads/Tails").

## When to Use
1. **Goal**: To see if the observed distribution of two categories differs from an expected distribution (usually 50/50).
2. **Data**: Nominal (Binary/Dichotomous).
3. **Design**: Often used for a single sample compared against a known probability (e.g., chance).

---

## Relationship with the Sign Test
In OCR Psychology, the **[[Sign Test]]** is the most common version of a Binomial Test you will use.
- The Sign Test is a **Binomial Test** where the probability ($p$) of a "+" or "-" is assumed to be **0.5** (50%) under the null hypothesis.
- It calculates the probability of getting the observed number of "successes" (the smaller sign count) by chance.

---

## How it Works (The "Binomial Distribution")
The test uses the **Binomial Formula** to calculate the probability of getting $k$ successes in $n$ trials.
- **n**: The number of trials (sample size, excluding ties).
- **p**: The probability of success on a single trial (usually 0.5).
- **k**: The number of successes observed.

### Example Scenario
> A researcher wants to see if a coin is biased. They flip it 10 times and get 9 Heads and 1 Tail.
- Under the Null Hypothesis, the chance of Heads is **0.5**.
- A Binomial Test would calculate the probability of getting 9 or more Heads purely by chance.
- If this probability is **$\leq$ 0.05**, the coin is considered "biased" (Significant).

---

## Evaluation

| Strength | Weakness |
| :--- | :--- |
| **Simple**: Ideal for simple "either/or" data. | **Low Power**: Requires a large sample size to detect small effects compared to interval tests. |
| **No Distribution Assumptions**: Doesn't require the data to be normally distributed. | **Nominal Only**: Loses all "depth" of data if you convert scores into simple +/- signs. |

---

## OCR Key Tip
If you are asked about a test for **nominal data** in a **repeated measures design**, always refer to the **[[Sign Test]]**. If you are asked about a single sample with two categories, you are talking about the **Binomial Test**.
