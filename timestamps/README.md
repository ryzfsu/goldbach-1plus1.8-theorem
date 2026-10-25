# Timestamps

[OpenTimestamps](https://opentimestamps.org) proofs for the assets of release `v1`.
Each proof commits to the SHA-256 of the file below and is anchored in Bitcoin block
973119 (2026-10-25 19:59:28 UTC).

| file | SHA-256 |
|---|---|
| `goldbach-1plus1.8-theorem-v1.pdf` | `53b0718f7ebe423b1c017aa590e379337dcc0b4e67d041cce493dbba3cca5792` |
| `goldbach-1plus1.8-theorem-v1.tar.gz` | `ba2833cfe45dc3ebcb0237d719d80fe7f0c15217c50e57eec2b9114935c672aa` |
| `paper-ii-public-certificates-v11.tar.gz` | `cb9d7b96ce1323c9118d845f4dd701a0d830e8c610090deec88bd8792648e100` |

To verify, download the release asset into this directory and run

    pip install opentimestamps-client
    ots verify timestamps/<file>.ots
