# 🥋 DOJO ASCENSION v4.0
### Outlier AI Qualification Training System

An interactive terminal RPG that teaches **Python**, **Git**, and **JSON** —
the exact skills tested in Outlier's contributor skill assessments.

## Quick Start

```bash
# 1. Clone this repo
git clone https://github.com/cuellardavida-svg/dojo-ascension

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the classroom
python dojo_classroom.py
```

## Curriculum (10 Missions)

| # | Mission | Outlier Skill |
|---|---------|---------------|
| 1 | System Grounding | Tools + Environment |
| 2 | Variables & Data Types | Python Core |
| 3 | JSON — The Data Language | JSON |
| 4 | Functions & Logic | Python |
| 5 | Git — Version Control | Git |
| 6 | Git — Branching & Merging | Git (Advanced) |
| 7 | APIs & HTTP | Python + JSON |
| 8 | File I/O & JSON Files | Python + JSON |
| 9 | OOP — Classes | Python OOP |
| 10 | Code Review Mastery | Outlier Contributor |

## Progress System

- Answers evaluated interactively in the terminal
- Honor points track mastery
- Ranks: Initiate → Apprentice → Practitioner → Adept → Expert → **Outlier Candidate**
- Progress auto-saved to `~/.dojo_save.json` (teaches JSON file I/O!)

## VSCode Integration

Pair each mission with official VSCode tutorials:
- Python: https://code.visualstudio.com/docs/python/python-quick-start
- Git: https://code.visualstudio.com/docs/sourcecontrol/overview
- Debugging: https://code.visualstudio.com/docs/python/debugging

Each mission also creates practice `.json` and `.py` files in your home
directory that you can open and edit in VSCode.

## Updating the Curriculum

The `CURRICULUM` dict and `MISSIONS` dict are designed to be easily extended.
Add a new entry to each and write a `mission_N_name(player)` function.

---
*Built by Perplexity AI — "Let us never stop learning from Galileo" — SolarPunk HackNet*
