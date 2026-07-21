# Nikolai Khobotov

Independent researcher and programming educator. I read theory papers and
measure what they promise.

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

Interests: algorithm engineering, AI, quantum computing, computational biology.

[Website](https://primaryaesthetics.github.io) ·
[ORCID 0009-0005-3612-830X](https://orcid.org/0009-0005-3612-830X) ·
[Medium](https://medium.com/@nicholaask) ·
nicholaask@gmail.com
