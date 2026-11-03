# RCA-AgriVLM Simulation

Interactive reviewer simulation for **RCA-AgriVLM: Risk-Calibrated Agentic Retrieval and Cross-Evidence Verification for Reliable Agricultural Vision-Language Reasoning**.

## Launch the simulation

The public reviewer experience is deployed with GitHub Pages:

**https://pratikpatelresearch.github.io/RCA-AgriVLM-Simulation/**

## Reviewer experience

The simulation provides five connected research views:

1. **Case workspace** — select a frozen agricultural case, replay the accepted five-agent pipeline, and adjust the answer–abstain threshold.
2. **Evidence trace** — inspect structured visual cues, ranked AgBase evidence, provenance identifiers, and support–contradiction relationships.
3. **Model laboratory** — compare controlled A0–A5 variants at case and aggregate levels.
4. **Evaluation** — review calibration, selective prediction, external validation, and documented evidence boundaries.
5. **Human study** — experience the prepared blinded rating workflow using browser-local, non-transmitted responses.

## Scientific boundary

This is an interactive evidence-replay simulation built from frozen, accepted experimental artifacts. It does not execute live VLM inference, diagnose arbitrary images, transmit images or ratings, claim completed human-participant evaluation, or establish universal state-of-the-art superiority. Reviewers select among six built-in publication-safe case visualizations; each selection loads its corresponding frozen reasoning trace.

## Run locally

```bash
python3 -m http.server 8899
```

Then open `http://127.0.0.1:8899/`.

## Main implementation

The complete reproducible implementation, staged notebooks, configuration, and verification documentation are maintained in the private manuscript-review repository:

**https://github.com/pratikpatelresearch/RCA-AgriVLM**

Repository access may require reviewer credentials or an invitation until the authors release it publicly.

