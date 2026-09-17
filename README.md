# DVT – Baseball Databank (Executed)

This repository version adapts the experiments from the reference IPL DVT repository to the Baseball Databank.

Reference repository:
https://github.com/MichaelA63/DVT_dataset

Target repository:
https://github.com/KAMESH45/DVT

Dataset:
https://www.kaggle.com/datasets/open-source-sports/baseball-databank

## Experiments
- EX1 – EX 1A and EX 1B
- EX 2
- EX 3
- EX 4 – EX 4A and EX 4B
- EX 5 – EX 5A and EX 5B
- EX 6 – EX 6A, EX 6B and EX 6C (Power BI preparation)
- EX 7 – EX 7A and EX 7B (Tableau preparation)

## Execution status
All 13 Jupyter notebooks in this package were executed successfully with Python 3 and contain saved cell outputs. No code cell contains a recorded execution error.

The Power BI and Tableau experiments contain the Python preparation, calculated fields/measures and visual outputs. Native `.pbix` and `.twbx` files must be created in Power BI Desktop/Tableau Desktop.

## Baseball data mapping
The IPL delivery-level fields were replaced by appropriate Baseball Databank fields:
- season → yearID
- runs_off_bat / total_runs → R
- batting_team → teamID
- player-level analysis → playerID
- team performance → Teams.csv
- fielding category analysis → Fielding.csv
- Baseball-specific power metrics → HR
- Baseball-specific batting metrics → H, RBI, BB, SO, SB, AB, etc.

The notebooks use a small data-location helper so they can find the CSVs from the repository `data` folder or from a Colab upload.
