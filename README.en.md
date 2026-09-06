# amber-ollama

Weekly public benchmark results of Ollama Cloud models on the private **AMBER** suite — cases private, results public.
中文: [README.md](README.md)

## What this is

- One issue per week at `results/YYYY-Www.md`: same cases, same effort band, same harness, full library against the model lineup.
- Every issue reports: case-set size and hashes, per-case d2 scores and pass/fail, terminal states, cost and latency, environment fingerprint, and qualitative verdicts written under evidence discipline.
- Cases, oracles, transcripts, and intermediate artifacts are **never published** (see "Publication discipline").

## Publication discipline (red lines)

1. Publish only: scores and aggregates, cost, latency, qualitative verdicts.
2. Never publish: case content, oracles/graders, transcripts, candidate workspaces, or any intermediate artifact that could reconstruct a case.
3. Every issue pins: model ID, effort band, date (UTC), harness version, and per-case content hashes (bundle_sha). Hashes line up with the public hash manifest in [amber-eval](https://github.com/getaskclaw/amber-eval) so anyone can verify the case set has not changed.
4. Case IDs and case structure are private: public results refer to cases only by stable aliases (A-xxxxxxxx, hash-derived) plus bundle hashes; internal case IDs, variant names, and case descriptions never appear.
5. Tone: this is a community weekly measurement, not an attack on the vendor. Let the data talk; keep wording restrained.

## Results index

| Issue | Content | Verdict |
|---|---|---|
| (first issue in preparation) | — | — |

## Disclaimer

Not affiliated with or sponsored by Ollama. Scores are snapshots of a specific week and effort band — not procurement advice.
