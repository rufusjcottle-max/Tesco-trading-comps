Tesco Trading Comparables Analysis

A trading comparables ("comps") valuation of Tesco PLC against six listed grocery peers 
(J Sainsbury, Carrefour, Ahold Delhaize, Jerónimo Martins, Colruyt, Kroger), built from 
primary annual reports as a university finance project.

## What's in the model

- **Universe selection** — screening the UK/European grocery sector for genuine listed 
  peers, with documented reasoning for exclusions (private companies, mismatched end 
  markets, structurally different business models)
- **LTM financials** — Sales, Gross Profit, EBITDA, EBIT, Net Income and EPS spread 
  directly from each company's annual report
- **Full EV bridge** — Equity Value → Enterprise Value, including debt, cash, preferred 
  equity, and minority interest
- **Benchmark analysis** — EV/Sales, EV/EBITDA, EV/EBIT, P/E and Net Debt/EBITDA across 
  the peer set, read against Mean/Median/High/Low
- **Implied valuation** — a Low/Mid/High EV/EBITDA range applied to Tesco's own EBITDA 
  to produce an implied share price

## Key finding

Tesco trades at a **67% EV/EBITDA premium** to the peer median but only a **33% P/E 
premium**. Since EV/EBITDA capitalises Tesco's £7.7bn of IFRS 16 lease liabilities into 
Enterprise Value while P/E ignores debt entirely, a large part of the apparent EV/EBITDA 
premium reflects Tesco's lease-heavy store estate rather than a genuine equity-level 
valuation premium. Reading the two multiples together gives a materially different 
conclusion than looking at EV/EBITDA alone.

## A data issue I found and fixed along the way

Initial debt inputs for the peer set mixed two different bases — some companies' "Total 
Debt" included IFRS 16 lease liabilities, others didn't. This was distorting the model: 
Sainsbury's Enterprise Value was understated by ~£5.5bn (its lease liabilities alone), 
making it look implausibly cheap on EV/EBITDA (2.8x vs a peer median of ~4.1x). 
Restating all seven companies onto a consistent lease-inclusive basis corrected this, 
raising Sainsbury's EV/EBITDA to 5.3x — much closer to peers, and consistent with what 
its scale and margins would suggest.
