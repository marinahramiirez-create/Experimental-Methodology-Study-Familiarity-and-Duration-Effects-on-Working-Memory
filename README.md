# Experimental-Methodology-Study-Familiarity-and-Duration-Effects-on-Working-Memory
This study uses a 2x2 within-subjects design to test how familiarity and duration affect working memory in free recall. Using Repeated Measures ANOVA (F, p, \eta_p^2) in JAMOVI, results showed a significant effect for familiarity (p&lt;.001, \eta_p^2 =.756), but no impact for stimulus duration or their interaction.

# Effects of Word Familiarity and Stimulus Duration on Working Memory

This repository contains the materials, data, and findings of a cognitive psychology experiment investigating how **word familiarity** and **stimulus presentation duration** influence performance in a **free recall task**.

## Abstract
The study employed a **2x2 within-subjects factorial design** to analyze working memory (WM) performance. 20 participants (aged 18-30) were exposed to four word lists where two independent variables were manipulated:
1.  **Familiarity:** High vs. Low.
2.  **Presentation Duration:** Long (2000ms) vs. Short (1000ms).

After each list, participants performed a distractor task (arithmetic or Stroop) followed by a free recall test.

### Key Findings
*   **Familiarity:** Showed a significant effect on performance ($F(1,19) = 58.92, p < .001, \eta_p^2 = .756$). Familiar words were significantly easier to recall ($M = 6.45$) than unfamiliar ones ($M = 3.83$).
*   **Duration:** No statistically significant difference was found ($p = .385$).
*   **Interaction:** The interaction between familiarity and duration was not significant ($p = .182$).

## Conclusion
The study concludes that **word familiarity** is a critical determinant of performance in free recall tasks. The high effect size ($\eta_p^2 = .756$) suggests that pre-existing semantic representations in long-term memory significantly facilitate the retrieval process in working memory. 

In contrast, **increasing stimulus duration** from 1000ms to 2000ms did not yield significant improvements. This indicates that, for young adults, additional exposure time within this range is not a sufficient factor to enhance recall if the stimulus lacks familiarity. These results emphasize the necessity of controlling for linguistic familiarity in experimental memory designs.

## Tools & Methodology
*   **Experimental Design:** Built with [lab.js](https://lab.js.org/).
*   **Data Collection:** Hosted via Open Lab.
*   **Statistical Analysis:** Performed using **JAMOVI** (Repeated Measures ANOVA).
*   **Control Variables:** Controlled for age, gender, word length (5 letters), and inter-stimulus interval (ISI of 1250ms).

## Repository Structure
*   `/analysis`: JAMOVI files and statistical output.
*   `/data`: Raw and processed anonymized data.
*   `/experiment`: Exported `lab.js` study files.
*   `/docs`: Full research report in English and Spanish.

## Keywords
`free-recall`, `working-memory`, `word-familiarity`, `stimulus-duration`, `cognitive-psychology`, `experimental-design`.
