# Optimal packings of 15, 16, 17, 18 and 20 equal circles in a circle

Proofs that the classical packings of 15, 16, 17, 18 and 20 unit circles in a circle are optimal, together with a characterization of the optimal packings for 15, 16, 17 and 20. The proofs are computer-assisted and use exact rational arithmetic. Substantially LLM work.

Blog post with more details: https://nor-blog.pages.dev/posts/2026-10-11-circle-in-circle-packing-15-20/

## Contents

- `paper.pdf`: the paper.
- `circle-packings-supplementary-materials.zip`: verification programs, angle tables and certificate data. See README.txt inside the archive and Appendix H of the paper for more details.

## Verifying

Requires Python 3 and g++ or clang++ with C++17 and signed 128-bit integer support.

```
unzip circle-packings-supplementary-materials.zip
cd supplementary-materials
python3 -E -B verify.py
```
