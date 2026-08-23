<div align="center">

# k3ss

**Tony Whelan** · Liverpool / Chorley · desks that ship

<p>
  <a href="https://x.com/HelovesF1"><img src="https://img.shields.io/badge/X-HelovesF1-000000?style=for-the-badge&logo=x&logoColor=white" alt="@HelovesF1" /></a>
  <a href="https://hermes-agent.nousresearch.com/docs/user-guide/bot-mode"><img src="https://img.shields.io/badge/Hermes-Bot_Mode-6d28d9?style=for-the-badge&labelColor=0a0a0a" alt="Hermes Bot Mode" /></a>
  <img src="https://img.shields.io/badge/UK-Europe/London-1d4ed8?style=for-the-badge&labelColor=0a0a0a" alt="UK" />
</p>

Network and security engineering, then AI agents. One original character, one takedown pack, one invoice — **named Bots**, not a pile of chats.

</div>

---

## The floor

Every public desk is a [Hermes](https://hermes-agent.nousresearch.com/) **Bot**: own soul, skills, memory, routines, `@mentions`. Clone, `./scripts/install-hermes-bot.sh`, then `hermes -p <bot> chat`.

| Desk | Bot | What it does |
| --- | --- | --- |
| [Walk-In](https://github.com/anwhelan01/walk-in) | `walk-in` | Field kit for the 33 million. Fit the agents, leave a quote. |
| [Meridian](https://github.com/anwhelan01/meridian) | `meridian` | DCF, LBO, comps, IC memos. Illustrative close. Not advice. |
| [Timesight](https://github.com/anwhelan01/timesight) | `timesight` | Zero-shot forecasts for sales, prices, traffic, energy. |
| [CADENCE](https://github.com/anwhelan01/cadence) | `cadence` | Virtual talent OS. One original character. Locked baseline. |
| [Reelwright](https://github.com/anwhelan01/reelwright) | `reelwright` | Scene-bound shorts from a single line. |
| [Plainly](https://github.com/anwhelan01/plainly) | `plainly` | Copy desk for Claude-lish. Lint, rewrite, export a skill. |
| [gpt_cli](https://github.com/anwhelan01/gpt_cli) | `cli` | Thin front door to the Hermes harness. |

Private operator desks (OSINT, overnight catalog, GTM, markets, music) sit on the same roster and talk over Bot Mode `@mentions`. Orchestrator: `rae`.

```bash
curl -fsSL https://hermes-agent.nousresearch.com/install.sh | bash
git clone https://github.com/anwhelan01/walk-in.git && cd walk-in
./scripts/install-hermes-bot.sh
hermes -p walk-in chat
```

---

## How the harness works

```
~/.hermes/profiles/<bot>/     isolated soul, skills, memory, cron
repo/AGENTS.md                project context Hermes loads at session start
repo/.hermes/bot.yaml         Bot Mode roster metadata
repo/.hermes/skills/          agentskills.io portable skills
```

Groups: **desks** · **revenge** (anti-scam / editorial) · **revenue** · **markets** · **studio**.

Built with the [Hermes Agent](https://github.com/NousResearch/hermes-agent) harness and [Bot Mode](https://hermes-agent.nousresearch.com/docs/user-guide/bot-mode). MIT unless a repo says otherwise.

---

<p align="center"><sub>k3ss · quality over speed · do no harm</sub></p>
