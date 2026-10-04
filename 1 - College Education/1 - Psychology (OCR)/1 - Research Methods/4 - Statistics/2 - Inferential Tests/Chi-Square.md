#Education #OCR #Psychology #ResearchMethods

**Chi-Square ($\chi^2$)** is used to find a **difference** or **association** when your data is in categories (**Nominal Data**).

---

## The "Math-Free" Explanation
Imagine you want to see if more boys than girls like pizza. 
- You count how many actually do (**Observed**).
- You figure out how many you *would expect* to if there was no difference (**Expected**).
- If the gap between "Observed" and "Expected" is huge, the result is significant!

---

## The Formula Symbols (Simplified)

| Symbol | **What it means in plain English** |
| :--- | :--- |
| **$\chi^2$** | The final "Chi-Square" score you are trying to find. |
| **$O$** | **Observed Value**: The actual numbers you counted in your study. |
| **$E$** | **Expected Value**: The numbers you *expected* to see if nothing interesting was happening. |
| **$\Sigma$** | **Sigma**: This just means "Add them all up" at the end. |

---

## How to Calculate $E$ 
To find the **Expected (E)** value for any box in your table, use this simple rule:
> **$E = \frac{\text{Row Total} \times \text{Column Total}}{\text{Grand Total}}$**

### Example:
| | Likes Pizza | Hates Pizza | **Row Total** |
| :--- | :--- | :--- | :--- |
| **Boys** | 10 (O) | 5 (O) | **15** |
| **Girls** | 20 (O) | 5 (O) | **25** |
| **Col Total**| **30** | **10** | **40 (Grand Total)** |

To find the **Expected (E)** for "Boys who like pizza":
- Row Total (15) $\times$ Column Total (30) = 450.
- 450 $\div$ Grand Total (40) = **11.25**.
- So, $E = 11.25$.

---

## Step-by-Step Calculation

| Step | **What to do** | **Math Version** |
| :--- | :--- | :--- |
| **1.** | Subtract Expected from Observed. | $(O - E)$ |
| **2.** | Square that number (multiply it by itself). | $(O - E)^2$ |
| **3.** | Divide that by the Expected number. | $(O - E)^2 \div E$ |
| **4.** | **Add up** the results from every box in your table. | $\Sigma$ |

---

##  Worked Example: "Phone Brand vs Personality"
**Hypothesis**: There is an association between the type of phone someone has and whether they are an introvert or extrovert.

| | iPhone | Android | **Row Total** |
| :--- | :--- | :--- | :--- |
| **Introverts** | 15 ($O$) | 10 ($O$) | **25** |
| **Extroverts** | 20 ($O$) | 5 ($O$) | **25** |
| **Col Total** | **35** | **15** | **50 (Grand)** |

### Step-by-Step Calculation:
1.  **Find Expected ($E$) for each box**:
    - *Example (Introvert/iPhone)*: $(25 \times 35) \div 50 = \mathbf{17.5}$.
2.  **Calculate $(O - E)^2 \div E$ for each box**:
    - $(15 - 17.5)^2 \div 17.5 = \mathbf{0.36}$.
3.  **Sum them all up**: $\Sigma = 0.36 + 0.36 + 0.83 + 0.83 = \mathbf{2.38}$.
    - **Observed $\chi^2 = 2.38$**.
4.  **Critical Value**: For $df=1$ at 0.05, the Critical Value is **3.84**.
5.  **Conclusion**: Is $2.38 \geq 3.84$? **No.**
    *   *Result*: Not significant. There is no real association between phone brand and personality.

---

## Evaluation (Strengths & Weaknesses)

| Strength | Weakness |
| :--- | :--- |
| **Easy to count**: You don't need fancy measurements, just tallies of "how many." | **Need enough data**: It doesn't work well if you have fewer than 20 people or if your "Expected" numbers are very small (less than 5). |
| **Versatile**: Can be used for almost any "group vs group" study. | **Loses detail**: It only tells you "how many," not "how much" (e.g., it knows you like pizza, but not *how much* you like it). |

---

## OCR Exam Tip: Significance
For Chi-Square, your calculated number ($\chi^2$) must be **GREATER THAN OR EQUAL TO ($\geq$)** the Critical Value in the table to be significant.
- **Mnemonic**: Chi-Square is "Big" (looks like a fancy X), so it needs a **Big** observed value!
