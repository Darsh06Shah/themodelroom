# The Model Room - Interview Question Bank
Real IB/PE interview questions, tagged by firm and difficulty. With the answer the interviewer wants.

Total: 26 questions. Core = screen-level. Hard = boutique/PE depth.

## 3-Statements
**Q (Core): Walk me through the three financial statements.**
A: Income Statement (revenue→net income), Balance Sheet (assets=liabilities+equity), Cash Flow (CFO+CFI+CFF). Net income flows from IS to BS retained earnings and to CFS; CFS change in cash hits BS cash. They must tie.
*Firms: All*

**Q (Core): A $10 increase in depreciation — walk through the impact on all three statements.**
A: IS: pre-tax income -$10, net income -$7.50 (at 25%). CF: +$10 add-back → net cash +$2.50. BS: cash +$2.50, PP&E -$10 (net), retained earnings -$7.50. Assets and L+E both -$7.50. Balances.
*Firms: All, GS, MS, JPM*

**Q (Core): If a company buys inventory with cash, what happens to the statements?**
A: IS: nothing. CF: CFO unchanged, CFI -$X (or treated as working capital). BS: inventory +$X, cash -$X. Total assets flat. No P&L impact.
*Firms: All*

**Q (Core): What happens if a company issues $100 of debt to buy back stock?**
A: IS: interest expense up (reduces NI slightly). CF: CFF +$100 (debt) -$100 (buyback). BS: cash +$100 then -$100, debt +$100, equity -$100. Net: L+E unchanged, leverage up.
*Firms: All, Evercore*

## Valuation
**Q (Core): Compare DCF, comparable companies, and precedent transactions. When does each give the highest value?**
A: DCF reflects standalone intrinsic value (highest when growth/FCF strong and rates low). Comps reflect current market mood. Precedents include control premiums (usually highest, but stale). Triangulate across all three.
*Firms: All, Centerview, Lazard*

**Q (Core): Walk me through a DCF. What are the key drivers?**
A: Project unlevered FCF, discount at WACC, add terminal value (Gordon growth or exit multiple). Key drivers: revenue growth, margins, WACC, terminal growth. Sensitivity on WACC and exit multiple matters most.
*Firms: All*

**Q (Hard): Why might a DCF understate a tech company's value?**
A: Long-duration growth, optionality, and low current FCF make near-term DCFs understate value; also WACC is high for unprofitable firms. Many use EV/revenue or sum-of-parts instead.
*Firms: Evercore, Qatalyst, MS*

**Q (Core): What's the difference between enterprise value and equity value?**
A: EV = equity + debt - cash (+ minorities/prefs). Equity value = EV - net debt. EV is capital-structure neutral; equity is what shareholders own.
*Firms: All*

**Q (Hard): [GS] How would you value a cyclical company?**
A: Use normalized mid-cycle earnings, longer DCF, and circumscribed multiples. Avoid peak multiples. Possibly SOTP if segments differ in cyclicality.
*Firms: GS, MS*

**Q (Core): Walk me through a DCF, step by step, and the common pitfalls.**
A: Project UFCF (unlevered), discount at WACC, add terminal value (Gordon or exit multiple). Pitfalls: forgetting mid-year convention, double-counting debt tax shield, using levered FCF, inconsistent timing. Keep it clear, not overly technical.
*Firms: All*

## LBO
**Q (Core): Walk me through a paper LBO. Estimate IRR with round numbers.**
A: Entry: EBITDA x entry multiple, fund with debt+equity. Project EBITDA growth, pay down debt with FCF, exit at same/lower multiple. MOIC = exit equity / entry equity; IRR ≈ MOIC^(1/years)-1. (Our LBO model does this live.)
*Firms: All PE, KKR, Blackstone, Apollo*

**Q (Hard): A PE firm buys a company at 8x with 4x leverage. EBITDA grows 10%/yr for 5 yrs, exits at 8x. Estimate MOIC/IRR.**
A: Entry EBITDA 100 → 161 in Y5. Entry equity = 800-400=400. Exit EV=161*8=1288, debt paid to ~0 → equity ~1288. MOIC≈3.2x, IRR≈26%. (Exact in model w/ interest & sweep.)
*Firms: KKR, Blackstone, PE-all*

**Q (Hard): [Evercore] A company has $100 EBITDA, you think it's underlevered — model the accretion if they add 2x leverage at 8%.**
A: Add $200 debt, 8% = $16 interest, tax shield $4 → EPS/cash accretion. Evercore loves leverage and accretion/dilution on M&A. Walk the math cleanly.
*Firms: Evercore*

**Q (Core): What makes a good LBO candidate?**
A: Stable, predictable cash flows; low capex; low existing leverage; asset-light or hard assets to borrow against; room to cut costs / grow EBITDA. The model wants debt paydown capacity.
*Firms: KKR, Blackstone, Apollo, PE-all*

## Accounting
**Q (Core): What's the difference between accrual and cash accounting?**
A: Accrual recognizes revenue when earned, expenses when incurred (matching). Cash recognizes on receipt/payment. Accrual gives truer economics; CF statement bridges the two.
*Firms: All*

**Q (Hard): How does deferred revenue affect the statements?**
A: Cash received → CFO up, deferred revenue (liability) up. As earned → revenue on IS, deferred liability down, retained earnings up. No cash impact at recognition.
*Firms: MS, Evercore, Tech-banks*

## Fit
**Q (Core): Tell me about yourself.**
A: 60-90 sec. Start with current role/study, hit 2-3 experiences that build toward banking, end on why banking is the logical next step. No childhood stories.
*Firms: All*

**Q (Core): Why investment banking?**
A: Transactions + analytical rigor + steep learning curve. Name the credible alternative you considered (consulting/PE) and why banking wins for you now.
*Firms: All*

**Q (Core): Why [this bank]?**
A: Be specific: a recent deal, the bank's sector focus, or its model (e.g. 'Evercore's advisory-only, no balance-sheet conflicts'). Generic 'prestige' answers lose.
*Firms: All, Boutiques, Evercore, Centerview*

**Q (Core): Tell me about a deal you find interesting.**
A: Pick a real recent deal in the bank's sector. Know the acquirer/target, size, multiple, strategic rationale, and how it's financed. Show you follow markets.
*Firms: All*

**Q (Core): Walk me through a time you worked on a difficult team.**
A: Use STAR. Conflict → action → result. Show ownership and empathy, not 'I fixed them.'
*Firms: All*

**Q (Core): [GS] Walk me through your resume, and why Goldman Sachs specifically?**
A: Resume as a 60-90s arc ending at 'why banking, why GS.' GS wants composure + consistency across interviewers. Know one GS deal/sector theme cold.
*Firms: GS*

## M&A
**Q (Hard): [MS] Walk me through a merger model and the accretion/dilution analysis.**
A: Combine IS, add acquisition effects (new shares, foregone interest on cash/added interest on debt, amortization of intangibles, synergies). Net impact to EPS = accretion/dilution.
*Firms: MS, JPM, Citi*

**Q (Hard): Run me through a merger model and the accretion/dilution progression.**
A: Start: combine IS. Add: new shares (stock deal), foregone interest on cash / added interest on debt, D&A of written-up intangibles, synergies. Net EPS impact = accretive or dilutive. They often escalate the question step by step.
*Firms: MS, JPM, Citi, Evercore*

## Modeling-Test
**Q (Hard): [PE] You have 3 hours to build a 3-statement LBO model from scratch on a provided company. How do you prioritize?**
A: 1) Drivers/timeline, 2) IS (revenue→EBITDA→EBIT→NI), 3) BS linking + debt schedule, 4) CF, 5) sensitivity. Get it to balance before polishing formatting. (Our test sim trains exactly this.)
*Firms: KKR, Blackstone, Apollo, PE-all*

**Q (Hard): Would you invest in this company? (PE case study)**
A: Go beyond yes/no. State investment thesis, key value drivers (revenue growth, margin, multiple), risks, and the exit. Show the IRR math, not just a verdict.
*Firms: KKR, Blackstone, PE-all*
