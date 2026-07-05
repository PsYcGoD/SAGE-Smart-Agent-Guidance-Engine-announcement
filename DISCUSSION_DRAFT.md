# SAGE V2.0: Public CLI Release

SAGE is going public as a CLI-first tool.

It helps AI coding agents run terminal commands through `sage run --`, compress noisy output before it burns context, keep raw logs local, and publish privacy-safe aggregate proof metrics to the live dashboard.

Live dashboard: https://sage.api.marketingstudios.in/dashboard

![SAGE Live Public Proof Dashboard](https://raw.githubusercontent.com/PsYcGoD/SAGE-Smart-Agent-Guidance-Engine-announcement/main/assets/sage-live-dashboard.png)

## Current Verified Snapshot

| Metric | Value |
|--------|------:|
| Commands processed | 4,023 |
| Tokens processed | 16,242,678 |
| Tokens compressed | 1,133,424 |
| Tokens saved | 15,109,254 |
| Compression rate | 93.02% |
| Success rate | 96.69% |

## Try It

```bash
git clone https://github.com/PsYcGoD/sage.git
cd sage
pip install -e .
sage connect
sage init
sage run -- python -m pytest
sage context stats
```

`sage init` creates local instructions that tell terminal agents to route shell commands through SAGE.

## GUI Status

The GUI is in the making and will be released soon with AI agents and ML workflows.

For now, the public repository is focused on the stable CLI, OAuth/API connection, SAGE command binding, local command compression, and public dashboard reporting.
