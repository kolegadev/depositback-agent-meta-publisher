# depositback-agent-meta-publisher

Publishes Instagram Reels, carousels, and Facebook Group content

## DepositBack Agent Network — Distribution

Part of the DepositBack autonomous marketing system.

## Quick Start

```bash
git clone https://github.com/kolegadev/depositback-agent-meta-publisher.git
cd depositback-agent-meta-publisher
pip install -r requirements.txt
python runtime/main.py
```

## Structure

```
.
├── SKILL.md, manifest.json, README.md
├── runtime/main.py
├── skills/skill_resolver.py, noop.py
├── data/inbox/, data/outbox/
└── .github/workflows/heartbeat.yml, scan.yml
```

## License

MIT — DepositBack Agent Network
