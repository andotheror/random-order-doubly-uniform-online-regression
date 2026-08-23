# Random Order Enables Doubly-Uniform Online Regression

## Abstract

\sloppy Online square-loss regression admits no sublinear regret bound that is simultaneously independent of the comparator norm and covariate scale in dimension above one when covariates are adaptive. We show that uniformly shuffling only the covariates changes the answer sharply, even if bounded labels remain fully adaptive. The unregularized Vovk-Azoury-Warmuth forecaster has expected regret at most $B^2\sum_{t\le T}\min(r,t)/t$, where $r$ is the final design rank. The result needs no norm, condition-number, distributional, or ambient-dimension bound. Its core is a distributional theorem for online leverage. Conditional on any fixed covariate multiset, the leverage sum is dominated in Laplace transform by $r+\sum_{t=r+1}^T\mathrm{Bernoulli}(r/t)$. This yields Bennett tails, an exact expected rank-profile formula, and kernelization by finite-span reduction. The domination is asymptotically exact in distribution already in one dimension. A Bayesian lower bound proves the minimax rate $\Theta(B^2r\log(eT/r))$ and recovers leading constant one in the large-block regime. Finally, entropy transport quantifies degradation under imperfect shuffling. The result isolates exchangeable covariate arrival as enough to recover the transductive logarithmic rate without randomizing the labels or revealing the final Gram matrix.

## Contributions

First, we prove the Poisson-binomial Laplace domination and Bennett concentration of random-order online leverage. Second, we combine it with a pathwise VAW inequality to obtain high-probability doubly-uniform regret against adaptive labels. Third, we establish minimax sharpness and distributional sharpness. Fourth, we give exact rank-profile, Hilbert-space, and imperfect-shuffle extensions.

## Keywords

online regression, random order, uniform guarantees, sequential prediction, regret bounds, realizable learning

## Files

- `main_old_2026-08-12.pdf`, the paper as first published, with its OpenTimestamps proof `main_old_2026-08-12.pdf.ots`.
- source: `aistats2026.sty`, `appendix.tex`, `checklist.tex`, `main.tex`, `references.bib`.
- also: `main.bbl`.
