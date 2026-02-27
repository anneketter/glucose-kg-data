# glucose-kg-data

CSV files for this repository should be stored in `data/csv/`.

## Upload CSV files from your machine

From this workspace, copy your CSV files into `data/csv/`, then run:

```bash
git add data/csv/*.csv
git commit -m "Add CSV data files"
git push origin main
```

If your files are in subfolders, use this instead:

```bash
git add data/csv
git commit -m "Add CSV data files"
git push origin main
```