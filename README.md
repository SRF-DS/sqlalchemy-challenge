# Surfs Up: Climate Analysis + Flask API

## Problem
Climate observations trapped in SQLite are more useful when you can analyze them in pandas *and* expose summary routes over HTTP.

## What we built
Under `SurfsUp/`:
- SQLAlchemy ORM access to climate SQLite data
- Exploratory climate notebook (`climate_starter.ipynb`)
- Flask API (`app.py`) serving precipitation / station / temperature style endpoints

## How to run
```bash
pip install sqlalchemy flask pandas matplotlib jupyter
cd SurfsUp
jupyter notebook climate_starter.ipynb
python app.py
```

## Stack
Python · SQLAlchemy · SQLite · Flask · pandas · Matplotlib

## Fun closer
Beach-day energy, measured in degrees and precipitation inches, served JSON-style.
