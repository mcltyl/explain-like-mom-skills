# Explain Like Mom 👩

**Explain crypto/AI/your job to parents without their eyes glazing over.**

"So what do you actually DO at work?" Your mom asks this every family gathering. You've tried explaining. She nodded politely. She still has no idea.

This Agent Skill translates jargon-heavy content into plain language with relatable analogies. Stop saying "I'm a DevOps engineer optimizing CI/CD pipelines" and start saying "I make sure the website doesn't break."

Works with Claude Code, Codex CLI, OpenClaw, and any Agent Skills-compatible tool.

---

## The Problem

- Tech jargon makes people's eyes glaze over
- You know your work matters but can't explain why
- Good analogies are hard to create on the spot
- "It's complicated" isn't an answer

**This skill solves it:** Jargon in, plain language out.

---

## Installation

### npx skills
```bash
npx skills add git@github.com:mcltyl/explain-like-mom.git
```

### Claude Code / Codex CLI
```bash
git clone https://github.com/mcltyl/explain-like-mom.git ~/.claude/skills/explain-like-mom
```

### OpenClaw
```bash
git clone https://github.com/mcltyl/explain-like-mom.git ~/.openclaw/skills/explain-like-mom
```

---

## Skills

| Skill | Description |
|-------|-------------|
| [explain-like-mom](skills/explain-like-mom) | Jargon → plain language with relatable analogies |

---

## Example Translations

### Jobs

| You Say | Mom Hears |
|---------|-----------|
| "DevOps Engineer" | "I make sure the website doesn't break — like a building superintendent for tech" |
| "Data Scientist" | "I find patterns in big piles of information — detective with spreadsheets" |
| "Product Manager" | "I decide what features to build — like a movie director for apps" |
| "ML Engineer" | "I teach computers to recognize patterns — dog trainer for computers" |

### Concepts

| Technical | Mom-Friendly |
|-----------|--------------|
| **API** | "A waiter — you tell them what you want, they get it from the kitchen" |
| **Cloud** | "Renting a piece of a giant computer instead of buying your own" |
| **Blockchain** | "A notebook everyone has a copy of — can't erase old pages" |
| **Machine Learning** | "Computers learn like you learned what a cat looks like — lots of examples" |
| **Bug** | "A typo in the instructions — '10 cups of salt' instead of '1 teaspoon'" |

### AI-Specific

| Concept | Plain English |
|---------|---------------|
| **ChatGPT** | "A computer that learned to write by reading the entire internet" |
| **Hallucination** | "When AI makes stuff up confidently — like a BS-er in a meeting" |
| **LLM** | "A computer that's really good at predicting the next word" |
| **Prompt** | "The instructions you give the AI — better question, better answer" |

---

## The Framework

```
Technical Explanation
        ↓
Ask: What does it DO? Why care?
        ↓
Find analogy from everyday life
        ↓
Test: Would mom understand?
        ↓
Plain Language Output
```

---

## Commands

```
"Explain [concept] like I'm explaining to my mom"
"Translate this job description for normal people"
"ELI5: [technical topic]"
"How do I explain [my job] at Thanksgiving?"
"Make this jargon-free: [text]"
```

---

## Analogy Domains

| Tech Area | Analogy Pool |
|-----------|--------------|
| Software | Kitchen, restaurant, building |
| Networks | Roads, plumbing, postal service |
| Data | Library, filing cabinet |
| Security | Locks, guards, ID checks |
| AI | Interns, dog training |

---

## The Mom Test

Before any explanation, ask:
- Would she nod or look confused?
- Could she explain it to someone else?
- Does it create the right mental picture?

If the answer is "no" to any — simplify further.

---

## License

MIT

---

## Support

If this helps you explain your job:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat&logo=buy-me-a-coffee)](https://buymeacoffee.com/mclty)
