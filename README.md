### Briek Van den Berg

Business Engineering (Financial Engineering track) student at KU
Leuven, BSc, expected June 2027. I build quant-finance projects from
scratch to actually learn the material — pricing, backtesting,
empirical methodology — rather than follow tutorials.

**[american-option-pricing](https://github.com/BriekVandenBerg/american-option-pricing)**
— LSM Monte Carlo pricer for American options on WTI crude futures,
plus a neural-net surrogate trained to reproduce it near-instantly
(~$0.09 RMSE, close to LSM's own $0.05 noise floor). Honest speed
comparison in the repo is against a binomial tree, not LSM. Greeks
checked against closed-form Black-76.

**[backtesting-engine](https://github.com/BriekVandenBerg/backtesting-engine)**
— A backtester with a real cash ledger (margin, borrow fees, interest
on cash), not a percentage-return shortcut. Runs a trend-following and
a cointegrated pairs strategy; reports Sharpe with a proper
significance test rather than just the point estimate.

**[earnings-event-study](https://github.com/BriekVandenBerg/earnings-event-study)**
— Event study on real earnings announcements. Announcement-day effect
is large and significant (t=8.38); the post-earnings-drift test comes
out null, checked against a synthetic panel with a known effect first
so the null is trustworthy rather than just a bug.

Currently prepping for 2027 quant/markets internship applications.
