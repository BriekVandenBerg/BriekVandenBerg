### Briek Van den Berg

Business Engineering @ KU Leuven (BSc, expected June 2027). Building
quant-finance projects from scratch to learn the material properly —
pricing, backtesting, and empirical methodology, not tutorials.

**[american-option-pricing](https://github.com/BriekVandenBerg/american-option-pricing)**
— LSM Monte Carlo American option pricer (WTI crude futures), with two ML
surrogates trained to reproduce it near-instantly. Neural net matches LSM
to ~$0.09 RMSE (near LSM's own $0.05 Monte Carlo noise floor) at
~50,000x the query speed; Greeks validated against closed-form Black-76.

**[backtesting-engine](https://github.com/BriekVandenBerg/backtesting-engine)**
— Real dollar-based backtesting framework (margin, financing costs, a
real cash ledger) for a trend-following and a cointegrated pairs
strategy. Sharpe reported with a proper significance test (Mertens/Lo)
— honest results, including where they don't clear significance.

**[earnings-event-study](https://github.com/BriekVandenBerg/information-diffusion-model)**
— Event-study methodology on real earnings announcements: a clean
t=8.00 announcement-day effect, and a post-earnings-drift test validated
on synthetic data (recovers a known effect exactly) before trusting its
null result on real data.

Prepping for 2027 quant/markets internship applications.
