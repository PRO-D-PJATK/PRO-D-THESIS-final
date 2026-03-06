# Diploma Thesis Tasks — Project Navigation

This document is the **navigation index** for the diploma thesis task set. It is not the main project readme; it explains how to find and use the individual task descriptions.

---

## How to Use This Repository

Tasks are ordered to follow the typical structure of an engineering thesis. Each task is in a separate file numbered **01** through **11**. Complete them in order where it makes sense; some tasks (e.g. data description and exploration) can be refined in parallel with writing.

- **Tasks 01–06** correspond to the main thesis chapters (introduction, literature review, data, preprocessing, architecture, models).
- **Task 08** is the summary chapter (conclusions and future work).
- **Task 09** lists formal and editorial requirements (formatting, length, citations).
- **Task 10** is a **self-assessment checklist** (0 points, same deadline as Task 11) so you can verify completeness before final submission.
- **Task 11** is the final task: comprehensive summary of the entire thesis.

All tasks except Task 10 are graded (e.g. on a scale of 10 points). Task 10 is for your own checking only.

---

## Task Index (with links)

| #   | File   | Task description |
|-----|--------|------------------|
| 01  | [01.md](01.md) | **First chapter (Introduction)** — Background, motivation, aims, scope, thesis structure |
| 02  | [02.md](02.md) | **Literature review** — Conducting and writing the literature review, citing sources |
| 03  | [03.md](03.md) | **Describe and document different data types** — Tabular, text, image, audio, video; structure, metadata, ethics |
| 04  | [04.md](04.md) | **Data exploration, standardization, and normalization** — EDA, preprocessing pipeline, documentation |
| 05  | [05.md](05.md) | **IT system architecture** — System design, components, deployment, security |
| 06  | [06.md](06.md) | **Describing and preparing ML models** — Problem formulation, architecture, training, evaluation, interpretation |
| 08  | [08.md](08.md) | **Summary chapter** — Overall summary, conclusions, future work |
| 09  | [09.md](09.md) | **Aggregated formal and editorial requirements** — Format, length, citations, bibliography, binding |
| 10  | [10.md](10.md) | **Self-assessment (0 points)** — Evaluation checklist; same deadline as Task 11; for self-check only |
| 11  | [11.md](11.md) | **Comprehensive summary of the entire thesis** — Final task; full-thesis overview and checklist |

---

## Recommended Order of Work

1. **01** → **02** → **03** → **04** → **05** → **06** (main thesis body)
2. **08** (summary chapter)
3. **09** (apply formal requirements throughout and before submission)
4. **10** (self-assessment; use before submitting Task 11)
5. **11** (comprehensive summary; final submission)

---

## Notes

- All task descriptions are in **English**.
- Keep your thesis text consistent with the structure and requirements described in these tasks.
- For submission and binding rules (length, font, margins, etc.), follow **Task 09** and your institution’s template.

---

## Publishing this repository to GitHub (PRO-D / PRO-final)

This folder is a **standalone Git repository**. To publish it as `PRO-D/PRO-final` on GitHub:

1. **Create the organization** (if it does not exist): GitHub → Your profile → Organizations → New organization → name it `PRO-D`.
2. **Create the repository**: In organization `PRO-D`, create a new repository named `PRO-final` (do not add a README or .gitignore).
3. **Push from this folder** (use the access token from `.env` in the parent directory):
   ```bash
   cd Zadania_PRO3_D
   git remote add origin https://<YOUR_GH_TOKEN>@github.com/PRO-D/PRO-final.git   # if not already added
   git push -u origin main
   ```
Replace `<YOUR_GH_TOKEN>` with the value of `GH_API_TOKEN` from `.env`.
