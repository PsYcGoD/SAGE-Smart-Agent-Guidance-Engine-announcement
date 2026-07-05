# S.A.G.E V2.0 Public Announcement

Smart Agent Guidance Engine is public as a CLI-first tool.

Use SAGE to connect with GitHub OAuth, install the `sage` command, bind local agent instructions, run commands through `sage run --`, and report privacy-safe aggregate stats to the live public dashboard.

Live dashboard: https://sage.api.marketingstudios.in/dashboard

![SAGE Live Public Proof Dashboard](assets/sage-live-dashboard.png)

## Current Proof Snapshot

| Metric | Value |
|--------|------:|
| Commands processed | 4,023 |
| Tokens processed | 16,242,678 |
| Tokens compressed | 1,133,424 |
| Tokens saved | 15,109,254 |
| Compression rate | 93.02% |
| Success rate | 96.69% |

## Quick Start

```bash
git clone https://github.com/PsYcGoD/sage.git
cd sage
pip install -e .
sage connect
sage init
sage run -- python -m pytest
sage context stats
```

## GUI Status

The GUI is in the making and will be released soon with AI agents and ML workflows.

For now, GUI source, GUI-only dependencies, and GUI tests are not included in the public repo. The public release is CLI-first so developers can use SAGE now without the unstable desktop app.

## Privacy

Raw commands, outputs, file paths, and logs stay local by default. The public dashboard receives aggregate proof metrics only.
