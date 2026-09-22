# SPC5004: Tools and Applications of Generative AI

Coursework for **SPC5004**, Queen Mary University of London, 2026/27.

## Structure

| Folder | What goes in it |
| --- | --- |
| `lectures/` | Lecture slides, notes taken in class, reading |
| `exercises/` | Weekly lab work and practice notebooks |
| `assessments/` | Graded submissions (one folder per assessment) |
| `projects/` | Larger pieces of work |
| `data/` | Datasets. Anything big or private is gitignored — see below |
| `notes/` | My own write-ups, summaries, revision material |

## Setup

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

Note: on this machine a bare `python` is the Microsoft Store stub. The real one is at
`%LOCALAPPDATA%\Programs\Python\Python313\python.exe`.

## Data

`data/` is tracked but its contents are ignored by default, so raw datasets never get
committed by accident. To deliberately track a small file:

```bash
git add -f data/small_file.csv
```

## AI usage

Where AI assistance is used in a submission, note it inline in that file — same convention
as SPC4003.
