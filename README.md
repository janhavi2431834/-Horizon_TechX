# Horizon TechX Internship — Task Submissions

This repository contains tasks completed for the Horizon TechX internship,
organised by domain. Each domain's PDF asks for 2–3 out of 4 listed tasks.

> **Note on repo naming:** the official instructions ask for one GitHub repo
> per project, named `HorizonTechX_ProjectName`. This repo groups everything
> in one place for convenience — if your submission form specifically wants
> separate repos, just split each folder below into its own repo with that
> naming pattern before submitting.

## Frontend Development (3 of 4 tasks)

| # | Task | Folder | Tech Used |
|---|------|--------|-----------|
| 1 | Image Gallery | `Frontend_ImageGallery/` | HTML, CSS, JavaScript |
| 2 | Calculator | `Frontend_Calculator/` | HTML, CSS, JavaScript |
| 4 | Music Player | `Frontend_MusicPlayer/` | HTML, CSS, JavaScript |

Each is a single self-contained `index.html` — just open it in a browser,
no build step or server needed.

### Image Gallery
A filterable photo gallery (Terrain / Structure / Street) with a full lightbox:
click any frame to view it full-size, step through with the arrow buttons or
← → keys, and close with Esc or the ✕ button.

### Calculator
A hardware-inspired calculator UI supporting +, −, ×, ÷, percent, backspace,
and clear, with full keyboard support and a running expression display.

### Music Player
A playlist-driven audio player with play/pause/next/previous, a draggable
progress bar, volume control, and a clickable track list. Uses freely-licensed
SoundHelix demo tracks and Picsum placeholder art so it works out of the box.

*(Task 3, Portfolio Website, was skipped since it needs your personal
projects/resume content — happy to build it once you share what should go
in it.)*

---

## Python Programming

⚠️ **Heads-up:** `Task1_Calculator/` and `Task3_Student_Analysis/` below were
built *before* your official Python-track PDF arrived, so they don't actually
match that task list (Hangman, Stock Portfolio Tracker, Task Automation,
Chatbot). Only Hangman lines up. Let me know if you want the real 2–3 tasks
(e.g. Stock Portfolio Tracker + Chatbot) built to replace these.

| # | Task | Folder | Tech Used | Matches official list? |
|---|------|--------|-----------|--------------------------|
| — | Simple Calculator | `Task1_Calculator/` | Python (standard library) | ❌ not on the list |
| 1 | Hangman Game | `Task2_Hangman/` | Python (`random`) | ✅ |
| — | Student Performance Analysis | `Task3_Student_Analysis/` | Python, Pandas, NumPy, Matplotlib | ❌ not on the list |

```bash
cd Task2_Hangman
python hangman.py
```

---

## Machine Learning & Power BI

Not started yet. Once you're ready, tell me which 2–3 tasks per domain you
want and I'll build those next (ML tasks need real datasets and are
noticeably heavier — Credit Scoring and Disease Prediction are the most
approachable of the four).

---

## Requirements

- Frontend tasks: any modern browser, no install needed.
- Python tasks: Python 3.8+. `Task3_Student_Analysis` additionally needs
  `pandas`, `numpy`, `matplotlib` (see its `requirements.txt`).

## Author

Completed as part of the Horizon TechX Internship Program.
