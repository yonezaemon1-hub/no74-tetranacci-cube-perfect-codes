# Research No.74 — preprint v1.0

**Exact 1-perfect-code classification of the fourth-order generalized Fibonacci cubes**

**Ryutaro Yonezu — Independent Researcher**

Manuscript date: 2026-11-18. Version: 1.0. Language: English.

For every integer n >= 1, the fourth-order generalized Fibonacci cube Q_n(1111), induced by binary words avoiding 1111, has a 1-perfect code if and only if n=1 or n=3. The infinite statement is proved analytically in the manuscript. Finite checks are corroboration.

## Scope and verification

AI-assisted; NOT PEER REVIEWED; NOVELTY INCONCLUSIVE; REFERENCES PARTIAL. No proof-assistant formal verification and no priority claim. An independent AI mathematical audit of the frozen v0.1 proof reported PASS. The author reported Windows FULL PASS for v0.1. The v0.2 editorial changes preserve the mathematical core. Neither the AI audit nor the author Windows run is a new execution of this v1.0 wrapper. An auditor separately reported CaDiCaL SAT checks for n=1..12; that code and certificates were not provided and are not part of this reproduction package.

The mathematical core of No74_v1.0.md from “## Model” through the text immediately before “## Relation to prior work” is byte-identical to the frozen v0.1 source and has SHA-256 `4f7623f8479cce3a9469d2d530f9fe2822c92f9e35855b6b401dffbd35663b45`. The TeX and PDF use equivalent mathematical typography.

## Reproduction

Unzip No74_v1.0_reproduction.zip. With Python 3.10 or later, run `python -B -I verify_manifest.py` and then `python -B -I verify.py` from the extracted directory. The output must match EXPECTED_RESULTS.txt (CRLF and LF line endings are equivalent). The final line retains its historical “INDEPENDENT AUDIT PENDING” wording from the frozen verifier; a later independent AI audit reported PASS. This finite script does not formally prove the result for all dimensions.

## Prior work

The result concerns fixed s=4 only and does not solve Mollard’s general Conjecture 3.1 or classify all s>=5. No.71 covers s=3: https://doi.org/10.5281/zenodo.24295940. The manuscript gives the targeted literature comparison; it does not establish priority.

## Rights

Copyright (c) 2026 Ryutaro Yonezu. All rights reserved. Public access to these files does not grant an open license. See LICENSE.txt.
