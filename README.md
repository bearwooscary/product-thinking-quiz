# Product Thinking Quiz

Static, dependency-free pages built around the Institute of Digital Government's
[Product Thinking learning pathway](https://www.idg.gov.sg/product-thinking/).
Open any file directly in a browser — there is no build step.

| File | What it is |
|---|---|
| `index.html` | The quiz app. 8 multiple-choice questions, one per module (metrics gets two), with a running score pinned to the top of the page. A wrong answer reveals the correct option and explains why. |
| `product-thinking-quiz.html` | A longer 14-question variant covering the same seven modules in more depth. |
| `product-thinking.html` | A single-statement intro page: title and tagline. |

## Coverage

Questions are drawn from the seven modules of the pathway:

1. Understanding the problem — why projects fail; Policy–Ops–Tech
2. Start with the whys — the 5 Whys, and choosing an *actionable* cause
3. Craft a clear problem statement — the 4Cs: Clarity, Consequence, Cause, Confirmation
4. Metrics — SMART, leading vs. lagging indicators, Value-Cost Ratio
5. Assumptions and risks — market/technical/team risk, staged de-risking
6. A good customer experience — the 11-Star exercise, compulsory services
7. Key takeaways — the three mindset shifts

## Notes

Each page is a single self-contained HTML file: styles and script inline, no
dependencies beyond a Google Fonts stylesheet link. Light and dark themes are both
handled via CSS custom properties.
