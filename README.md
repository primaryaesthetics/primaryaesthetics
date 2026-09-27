# Nikolai Khobotov

Independent researcher and programming educator. I read theory papers and
measure what they promise.

**[Out of Time](https://github.com/primaryaesthetics/out-of-time-tfm-credit)** —
a pre-registered out-of-time evaluation of the tabular foundation models
TabPFN-3 and TabICLv2 on credit default. Both are read on the origination
vintages of Lending Club and Freddie Mac, beside a weight-of-evidence
scorecard and a tuned gradient-boosting model. At the softmax temperature of
0.9 the packages ship, both models' mean probability on their own context
rows is 0.656 to 0.736 of the realised default rate on Lending Club; at 1.0,
observed over expected holds one. Every number in the paper traces to a
recorded run through a claim ledger.
[Paper DOI 10.5281/zenodo.22999138](https://doi.org/10.5281/zenodo.22999138) ·
[Code DOI 10.5281/zenodo.22994434](https://doi.org/10.5281/zenodo.22994434) ·
[Protocol DOI 10.5281/zenodo.22803068](https://doi.org/10.5281/zenodo.22803068)

**[psi-inference](https://github.com/primaryaesthetics/psi-inference)** —
critical values and p-values for population stability testing in Python: the
Yurdakul–Naranjo test of the PSI, the Population Resemblance Statistic, and
the effect-size and overlapping tests of du Pisanie et al. The last three had
no package in Python or R before it. With no population shift at all, the
delta-method z-test published for the PSI rejects in 97.4–97.6% of samples at
10 bins and a nominal 5%; the README shows the simulation.
[DOI 10.5281/zenodo.22342343](https://doi.org/10.5281/zenodo.22342343) ·
[`pip install psi-inference`](https://pypi.org/project/psi-inference/)

**[beyond-dijkstra](https://github.com/primaryaesthetics/beyond-dijkstra)** —
the first implementation of the 2026 Duan–Mao–Shu–Yin directed shortest-path
algorithm (arXiv:2602.07868), in Rust, gated bit-for-bit against a Python
reference. It is not faster than Dijkstra at any size you can store: the
faithful port trails by 38–182×, the most engineered variant by 1.8–2.2×. The
audit is the result: two lines of the printed pseudocode crash on ordinary
graphs, and the completeness clause of Lemma 3.7 is false as stated, with a
70-vertex counterexample and a hand proof that a one-line repair closes the
hole.
[Note DOI 10.5281/zenodo.21478493](https://doi.org/10.5281/zenodo.21478493) ·
[Code DOI 10.5281/zenodo.21473443](https://doi.org/10.5281/zenodo.21473443)

**[logtwothirds](https://github.com/primaryaesthetics/logtwothirds)** — a
verified Rust/Python implementation of the 2025 sorting-barrier shortest-path
algorithm (Duan–Mao–Mao–Shu–Yin, STOC 2025), benchmarked honestly against
Dijkstra. The engineered variant runs within 1.1–1.2× of Dijkstra at
n = 10⁶–10⁷ — the smallest published gap — and the study documents why no
practical input size crosses over.
[DOI 10.5281/zenodo.21284462](https://doi.org/10.5281/zenodo.21284462) ·
[`pip install logtwothirds`](https://pypi.org/project/logtwothirds/)

Interests: credit risk modelling, algorithm engineering, AI, quantum computing,
computational biology.

[Website](https://primaryaesthetics.github.io) ·
[ORCID 0009-0005-3612-830X](https://orcid.org/0009-0005-3612-830X) ·
[Medium](https://medium.com/@nicholaask) ·
nicholaask@gmail.com
