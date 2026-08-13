# IMG Southbank — Report & Interactive Tool

**File:** `IMG_Southbank_Report_and_Tool.html`
**Site:** 292–306 City Road, Southbank
**Status:** Private & confidential — internal discussion tool for IMG Investment Joint Stock Company and Purple Sand

## What this is

A self-contained, offline HTML file (no install, no internet connection needed — just open it in any browser) that presents the basement decision — build now on the current endorsed plan, or spend 3 months with Purple Sand reviewing it first — in two linked views:

- **Report tab** — the fixed, presentation-ready version with locked figures, for circulating to the board.
- **Tool tab** — the same analysis rebuilt with editable assumptions, for testing different numbers live in a meeting.

Both tabs share one page and the same underlying model, so the Tool's live output can always be checked against the Report's fixed numbers.

## Report tab

Static, non-editable. Structure:

1. **Key Summary** — IMG has asked Purple Sand to present two options/paths.
2. **Project Overview and Recommendation** — the basement cost risk (Hickory's $153M vs Purple Sand's $161.4M, basement alone $30–35M, flood-zone risk pushing Hickory toward ~$200M), Option 1 vs Option 2 side by side, and an Option 1 profit/loss table at both the original $161.4M and escalated $200M construction cost.
3. **Cost of the Review — Stage 1 & Stage 2** — Stage 1 (first 3 months, $110,000) and Stage 2 (months 4–12, $1,426,175) broken out separately, totalling $1,536,175, plus the basement removal saving ($30M conservative / $35M expected) that offsets it.
4. **Net Position** — Option 2's net position against Option 1's own profit/loss, across 8–12% NSA gain, 3%/8% sales cost, and both basement saving levels.
5. **The Decision** — summary paragraph: Option 2 nets $47M–$64M better than Option 1 on current costing.

## Tool tab

Same structure, but every input feeding the model is editable:

- Stage 2 run time (months 4 onward; 3–21 months, i.e. 6–24 months total)
- Stage 1 fee and Stage 2 monthly fee (both ex GST)
- Architect & consultant redesign budget
- Average annual land tax (pro-rated for run time)
- GST rate
- NSA sell rate ($/m²)
- Sales & marketing cost — low and high scenario (%)
- Basement removal saving — conservative and expected
- Option 1 construction cost (escalated — drives the Option 1 profit/loss table)

Changing any field live-updates: the Stage 1/Stage 2/total cost breakdown, the Option 1 profit/loss table (at both the original $161.4M and the editable escalated construction cost), and all four net-position tables (conservative/expected basement saving × low/high sales cost).

```
Net position = NSA profit uplift + basement saving − total inherited cost (Stage 1 + Stage 2)
```

Rows are colour-coded — green where Option 2 is net-positive at that combination, red where it isn't. Option 1's profit/(loss) is shown alongside for direct comparison and is always shown in red on current costing.

The base feasibility inputs (current NSA 17,900 m², GBA 26,901 m², base GRV $297.1M, and the other fixed cost lines — land, consultants, authorities, PM, building surveyor, marketing, legal, contingency, finance) are carried over from the original proposal and are not editable in this tool, since they don't move under either option.

## Key methodology notes

- The NSA uplift calculation assumes GBA is unchanged (efficiency comes from redesigning within the existing envelope), so land, hard construction, consultants, authorities, project management, insurance, marketing, legal, contingency and finance costs don't move. Only GST (1/11 of the extra GRV) and sales commission scale with the additional revenue.
- Option 1's profit/(loss) is recalculated from the same base feasibility, swapping in either the original $161.4M Purple Sand construction estimate or the escalated Hickory figure — everything else held constant.
- GST applies to the two Purple Sand fees (Stage 1 and Stage 2) only, not to the consultant budget or land tax.
- All figures are preliminary and indicative — consistent with the caveats in the underlying proposal, they're subject to detailed QS, GST, finance and design verification before being relied upon.

## Who to talk to about the assumptions

Land tax, PS fee, consultant budget, construction cost and basement saving figures were set based on the discussion with Pat on this project — adjust them directly in the Tool tab if any of those change.
