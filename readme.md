# Main

Goals:

1. Build keywords using synonyms
2. Build potential usernames using synonyms combination
3. Validate usernames to see if they are valid

# Usage

## Setup VENV

1. Install python
2. Setup .venv folder: `python -m venv .venv`
3. Activate virtual environment: `. .venv/Scripts/activate`

## Install Dependencies

`pip install -r requirements.txt`

## Run program

`python main.py`

# Dev details

## File Structure

```
.venv/
  |-- *
data
  |-- synonyms
    |-- *
      |-- raw
      |-- utilized
      |-- unique
  |-- usernames
    |-- potential
    |-- valid
```