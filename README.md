# Junior Data Analyst assignment: defect screening on component images

- `solution.ipynb`: the full solution (Parts A–E, plus an optional Part R on the research question). The summary and the answer to the research question are in the first cell.
- `predictions.csv`: 72 rows, `image_id,predicted_defect,score`, one per image in `test.csv`.
- `train.csv`, `test.csv`, `images/`: the data supplied with the assignment.

## Run
```
pip install -r requirements.txt
jupyter lab solution.ipynb   # then Run All (about 30–60 s, CPU only)
```
Keep the notebook in the same folder as `train.csv`, `test.csv` and `images/`. It regenerates `predictions.csv`. All randomness is seeded (`SEED = 42`).
