# Theorem (1 + 1.8) on the Goldbach conjecture

Ruiyi Zhang

DOI: [10.5281/zenodo.23649264](https://doi.org/10.5281/zenodo.23649264)

Every sufficiently large even integer `N` has a representation

    N = p + r q,    p, q prime,    r = 1 or r prime,    r <= q^(4/5).

This is Proposition (1 + a) of Li-Liu with `a = 1.8 = 9/5` (Li-Liu prove `a = 1.9`).

The proof uses a weighted sieve on shifted primes whose level of distribution exceeds one half,
taking the signed distribution estimates of [Z1] as input. Thirteen signed row estimates are
combined with a switched upper bound. In the Chen-constant normalization (no leading factor 2),
the certified endpoint is `D_lower = 1.83399665352036682372...`, which exceeds the
balanced-semiprime threshold `8 log(50009/39991) = 1.78838848345960807362...`; the remaining
coefficient is `0.04560360924375267422827... - o(1)`.

[Z1] R. Zhang, *Shifted primes in arithmetic progressions to large moduli with linear sieve
remainder weights*, Zenodo, 2026. DOI: 10.5281/zenodo.23615525.

## Contents

- `main.pdf` (102 pages)
- `source/` - LaTeX source: `main.tex`, the chapter files it includes, and `references.tex`
- `SHA256SUMS`

The numerical-certificate supplement `paper-ii-public-certificates-v11.tar.gz` (scripts, inputs,
full-precision outputs, finite-check run records, verification logs, environment records) is
attached to the release. Its SHA-256 is
`cb9d7b96ce1323c9118d845f4dd701a0d830e8c610090deec88bd8792648e100`; the root `SHA256SUMS`
inside it has SHA-256 `18eb23d96be1c096bd2d32a36a34d7e5d9da978e5494e7ae02851a7b74adb182`.
The archive README gives verification and reproduction commands.

## Build

    cd source
    pdflatex main.tex
    pdflatex main.tex
    pdflatex main.tex

## Citation

Ruiyi Zhang, *Theorem (1 + 1.8) on the Goldbach conjecture*, preprint, Zenodo, 2026. https://doi.org/10.5281/zenodo.23649264

```bibtex
@misc{zhang2026goldbach18,
  author    = {Zhang, Ruiyi},
  title     = {Theorem (1 + 1.8) on the Goldbach conjecture},
  year      = {2026},
  publisher = {Zenodo},
  note      = {Preprint},
  doi       = {10.5281/zenodo.23649264},
  url       = {https://doi.org/10.5281/zenodo.23649264}
}
```
