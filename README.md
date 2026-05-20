# Overview of Volatility Modeling

Deck 08 of the [Paul Wilmott Introduces Quantitative Finance &mdash; Companion Series](https://github.com/BrendanJamesLynskey/Wilmott_QF_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/Wilmott_QF_08_Volatility/

A guided tour of chapter 9 of *Paul Wilmott Introduces Quantitative Finance*
(2nd edition, Wiley, 2007) &mdash; what "volatility" actually means once you
look past the single number Black&ndash;Scholes asks for, and the families of
model built to explain why one number is never enough.

## What's inside

- The four kinds of volatility &mdash; actual, historical/realised, implied, forward
- Historical estimation, moving windows, exponential weighting
- GARCH(1,1) and EWMA &mdash; volatility clustering as a time-series property
- Range-based estimators: Parkinson, Garman&ndash;Klass
- Implied volatility by Newton's method on Black&ndash;Scholes
- Smiles, skews, and the empirical implied-vol surface
- Deterministic local volatility and the Dupire formula
- Stochastic volatility &mdash; Heston, Hull&ndash;White, SABR, rough vol
- Uncertain volatility (Avellaneda&ndash;Levy&ndash;Par&aacute;s) and the BSB equation
- **Interactive implied-vol smile explorer** &mdash; drag the quadratic smile
  coefficients $\sigma_0, a, b$ and watch the smile shape and the resulting
  Black&ndash;Scholes call-price curve update live, with a Newton-iteration
  demo that shows each step of the implied-vol root-find

Companion to chapter 9 of:

> Wilmott, P. (2007). *Paul Wilmott Introduces Quantitative Finance,
> Second Edition.* John Wiley &amp; Sons. ISBN 978-0-470-31958-1.

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
