# Meta Publisher

> **Agent**: `depositback-agent-meta-publisher`  
> **Group**: Distribution  
> **Product**: DepositBack — Security Deposit Demand Letter Service

## Purpose

Cross-posts TikToks as Reels, publishes carousel posts (6.90% engagement), and manages Facebook Group value-first answers with bio-only CTAs.

## DepositBack Context

DepositBack is a single-page, no-signup transactional product for US renters seeking to recover security deposits. The entire customer journey fits on one URL: landing page → 6-question form → Revolut payment → PDF emailed. Conversion rate target: **4% visitor-to-purchase minimum**.

## Inputs

- Reel/carousel assets from social-content-creator
- Community responses from community-engager

## Outputs

- Published Meta content URLs → analytics/funnel-analyst inbox

## Human Escalation Points 🛑

- Group moderation actions
- Ad account restrictions
- Influencer partnership posts

## Skills

| Skill | Description | Status |
|-------|-------------|--------|
| `noop` | Health check / pipeline verification | ✅ Active |
| `execute` | Primary function for this agent | 🔧 Planned |

## Workflow

1. Poll `data/inbox/` for task manifests from upstream agents.
2. Resolve required skills (local `skills/` or ClawHub fallback).
3. Execute workflow.
4. Write artifacts to `data/outbox/`.
5. Update `data/state.json`.

## Runtime

```bash
pip install -r requirements.txt
python runtime/main.py
```
