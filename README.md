# Growth Audit — DuoCards

**Live:** https://bterzic123.github.io/duocards-flow-rebuild/

Five ideas to unlock more revenue from the traffic DuoCards already has, plus a clickable prototype of the onboarding and paywall rebuilt in DuoCards' own design. Only the order of the screens changes; the mammoth, the speech bubbles, the level bars, the interest tiles, the A0–C2 card and the blue pill buttons are all theirs.

## The five ideas

| # | Idea | Screen | Potential outcome |
| :-- | :-- | :-- | :-- |
| 01 | Catch the close with your 3-month plan | Offer on close | ARPU +10–15% |
| 02 | Show what Premium unlocks on the paywall | Paywall | CR +10–20% |
| 03 | Move the speaking test past the paywall | Analysis | CR +10–15% |
| 04 | Read their answers back before the analysis | Your answers | CR +10–15% |
| 05 | Put Susan's quote and the faces at the price | Paywall | CR +5–10% |

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for DuoCards.

## Grounding

Every price, rating, quote and feature line comes from DuoCards' own published material: the App Store listing, duocards.com, the DuoCards FAQ and the in-app screens. The 3-month plan's price is left as a slot to confirm against the store.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?open=proto` to land on the prototype.
