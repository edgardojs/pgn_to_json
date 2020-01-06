# Requires

Python 3 
python-chess

pipenv (Optional but make sure you look at the Pipenv as the requirements.txt)

# pgn_to_json

Converts a PGN chess game file to JSON format. Python 3 implementation of https://github.com/Assios/pgn-to-json.

# Usage

cd <script directory>

pipenv shell
python pgn_to_json.py mygame.pgn

There are Pipfile and Pipfile.lock included for pipenv usage. This assumes there is a mygame.pgn file in the same folder

Pass in the .pgn files you want to convert as args.

