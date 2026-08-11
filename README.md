<p align="center">
  <h1 align="center">Verbalized Eval Awareness Under More Realistic Settings</h1>
  <p align="center"><strong>Measure when models talk about being evaluated as the eval environment looks more or less real.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Verbalized Eval Awareness Under More Realistic Settings**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Measure when models talk about being evaluated as the eval environment looks more or less real.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
