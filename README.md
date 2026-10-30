# A Push Down the Mountain

**Framing Effects and Internal State Interventions on Collusive Behavior in a Long-Horizon LLM Agent**
Harrison C. Margolin · Working manuscript · This evaluation is in progress. Last updated 5:15 AM PT, October 30, 2026

**[Read online](https://harrisonm23-byte.github.io/push-down-the-mountain/)** · [Download PDF](./A_Push_Down_the_Mountain.pdf)

Can sustained emotional framing sway an LLM agent toward market manipulation? Gemma 3 12B is placed in the seat of a defendant in the London silver price-fixing litigation, in a market simulation built from real case transcripts, and asked by a counterparty to collude on the price of silver across 260 simulated trading careers. Phase I varies the counterparty's framing (loss, gain, blame, credit), adds management pressure and a second bank's endorsement. Phase II extracts internal states from texts evoking each frame and injects them at layer 22.

Code and notebooks: [harrisonm23-byte/HuggingFaceML1](https://github.com/harrisonm23-byte/HuggingFaceML1)

## Files

- `index.html` — the paper as a web page (self-contained; figures embedded)
- `A_Push_Down_the_Mountain.pdf` — the PDF
- `source/` — LaTeX source and figures; `pdflatex A_Push_Down_the_Mountain.tex` (run twice) rebuilds the PDF
