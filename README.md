## Football matches result predictions
How to use?
1. Clone repository.
```sh
git clone https://github.com/bangetfres-09/football_predictions
```
2. Create and activate virtual environment for python.
```sh
# LINUX:
python3 -m venv football_preds
source football_preds/bin/activate

# WINDOWS:
python -m venv football_preds
football_preds/Scripts/activate
```
3. Install required packages (in virtual environment!).
```sh
pip install -r requirements.txt
```
4. Run the <a href="main_script.py">main_script.py</a> from console.
```sh
python scripts/main_script.py <LEAGUE_NAME>
```
Then results will be saved to `\output_tables` for league passed in the argument.
