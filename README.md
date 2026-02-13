# 🦦 Otterline — Free NBA + NHL Picks for OpenClaw

Get daily **free sample** sports betting winner picks (moneyline-style) directly through your OpenClaw agent. No API key required.

Otterline aggregates multiple signals into tiered picks for **NBA** and **NHL**.

## Install

```bash
npx clawhub@latest install otterline
```

Or paste this repo link into your OpenClaw chat and ask it to install.

## Usage

Try slash commands (OpenClaw) or plain English:

- `/otterline`
- `/otterline nba`
- `/otterline nhl`
- `/otterline date=2026-02-12`

- *"What are today's Otterline picks?"*
- *"Any elite NBA picks today?"*
- *"What's the best bet tonight?"*

## What You Get (Free)

Up to **4 sample picks per league per day** (tiers vary day-to-day):

What’s included per pick depends on the league:
- **NBA**: tier + picked team + (often) `consensus_count` and `combo_win_rate`
- **NHL**: tier + picked team + `score` and `moneyPuckWinProb`

Tier notes:
- **NHL** uses `Elite / Verified / Strong / Lean`
- **NBA** may include a `Pass` tier (not a bet)

## Example

```
🦦 Otterline NBA Picks — 2026-02-12 (free sample)
These are FREE sample picks. Showing 2 of 3 total picks today.

🔥 Elite (consensus: 3/3, combo win rate: 69%)
  Milwaukee Bucks @ Oklahoma City Thunder -> Oklahoma City Thunder

💪 Strong (consensus: 2/3, combo win rate: 67%)
  Portland Trail Blazers @ Utah Jazz -> Utah Jazz

Full slate → otterline.club/premium
```

## Want Every Pick?

The free skill gives you a daily sample. The full slate — every pick, every tier, every game — is available at **[otterline.club/premium](https://otterline.club/premium)**.

For entertainment only; bet responsibly.

## Leagues

| League | Engine |
|--------|--------|
| NBA | Chorus Consensus Engine |
| NHL | Vector-3 Decision Model |
| MLB | Coming soon |

## Links

- **Website:** [otterline.club](https://otterline.club)
- **Premium:** [otterline.club/premium](https://otterline.club/premium)
- **Twitter:** [@TheOtterline](https://twitter.com/TheOtterline)
