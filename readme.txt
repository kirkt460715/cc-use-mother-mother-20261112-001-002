County school estate allocation. Python 3.11+; standard library and SQLite.
All included observations are synthetic. No network is needed.
python3 estate_cli.py demo --fixture fixtures/county.json
python3 estate_cli.py solve --fixture fixtures/county.json
python3 estate_cli.py inspect --fixture fixtures/county.json
python3 estate_cli.py --help
python3 -m unittest discover -s tests -v
python3 -m compileall -q estate allocation assessments runs estate_cli.py
