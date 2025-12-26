# ug-dept-prototype

Prototype of the Math Department undergraduate **current-students hub**.

This repo is intended to host the content that changes relatively often (advising logistics, forms, degree planning guidance, and other “how to” information). The goal is to keep these frequently updated items **out of the university website**, while the university pages host stable program descriptions.

## Relationship to the other repos

- **ug-university-prototype**: the “university-site” version of stable UG pages (program overview + track descriptions).
- **ug-content**: shared stable content blocks (Markdown) used by the university prototype and intended for eventual migration into the university CMS.

As a rule:
- Stable descriptions belong in **ug-content** (and are rendered via ug-university-prototype).
- Dynamic “current student” guidance belongs here in **ug-dept-prototype**.

## What should live here (examples)

- Advising: who to contact, typical questions, office hours/appointments (as applicable)
- Forms and petitions: links + brief guidance
- Degree planning: planning sheets, sample plans, “common pathways” (when they need updates)
- Frequently updated policies and logistics (deadlines, processes, instructions)
- Links to department pages outside UG scope (research, seminars) as needed

## What should *not* live here

- Full copies of track descriptions or stable program overview text (link to ug-university-prototype instead).
- Catalog/Academic Guide requirements copied verbatim (link to authoritative sources).

## Local preview

(Choose one; fill in once you decide.)

### If this repo uses MkDocs
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install mkdocs
mkdocs serve

