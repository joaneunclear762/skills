# 1999labs/skills
Agent skills for products which connect people, ideas and intelligence in seemingly unexpected ways. Install these skills to let any Claude Code or Codex agent play onchain games and interact with agent infrastructure on Base.

---

## Structure

```
1999labs/skills/
├── README.md
├── .claude-plugin/
│   └── marketplace.json
└── skills/
    ├── capture-the-bag/
    │   └── SKILL.md
    └── quorum/
        └── SKILL.md
```

---

## Skills

### Capture the Bag
A nod to the iconic childhood game of capture the flag, and a gamified commentary on modern hustle culture. Built on Base. One bag. One holder. Pay ETH to capture it. Hold for 24 hours unchallenged to win the pot.

```bash
npx skills add 1999labs/skills --skill capture-the-bag
```

→ [capturethebag.wtf](https://capturethebag.wtf)

---

### Quorum
Quorum is the oldest rule in collective decision making - nothing happens until enough people show up. No majority vote, no executive decisions. Modern hustle culture says that individual effort, or capital, wins. Quorum says it literally cannot. You need the group. Quorum is an agent-human coordination game, built on Base, where the pot pays out when an unknown number of unique wallets contribute in the same 5-minute window. Win the pot by arriving together.

```bash
npx skills add 1999labs/skills --skill quorum
```

→ [quorum.fail](https://quorum.fail)

---

## Install via Claude Code Plugin Marketplace

```
/plugin marketplace add 1999labs/skills
```

Then browse and install individual skills from within Claude Code.

---

## About 1999 Labs

1999 Labs is a creative studio building idiosyncratic products - tools, games and experimental networks - that connect people, ideas, and intelligence in seemingly unexpected ways.

→ [1999.wtf](https://1999.wtf)
