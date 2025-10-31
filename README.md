# ML Specialization — Self‑Check & Exercise Pack
This repo is a **GitHub‑ready checklist + exercise set** aligned with Andrew Ng's *Machine Learning Specialization* (MLS).
Use it to track progress, answer theory prompts, and complete lightweight coding tasks (within MLS scope).

## How to use
1. Create a new GitHub repo and upload this pack, or fork it.
2. Each week, open the corresponding file under `tasks/` and `notebooks/`.
3. Tick boxes in **`PROGRESS.md`** and paste short answers or links to notebooks.
4. Keep commits small with clear messages (e.g., `feat: add k-means elbow check`).

## Environment (local or Colab)
```bash
conda env create -f environment.yml
conda activate mls-selfcheck
jupyter notebook
```
(Or open the notebooks in Google Colab directly.)

## Structure
- `tasks/` — theory & coding prompts + rubrics (8 mini‑modules).
- `notebooks/` — starter notebooks to implement solutions.
- `scripts/` — tiny helpers for metrics/data loading.
- `checklist.md` — single‑page self‑assessment.
- `PROGRESS.md` — your personal tracker.
