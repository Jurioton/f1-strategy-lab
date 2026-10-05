# F1 Strategy Lab

Analysing real Formula 1 race data to understand how tyre wear, pit stops, and safety cars shape race strategy. Built step by step, from data exploration to a strategy simulator.

**Status:** Work in progress. Currently at: data exploration.

## Goal
Build a tool that recommends pit stop strategy for a race, backed by a tyre degradation model, a FastAPI backend, and a dashboard.

## Roadmap
- [x] Project setup and first race loaded
- [ ] Stint analysis and tyre compound comparison
- [ ] Tyre degradation model
- [ ] FastAPI backend
- [ ] Strategy simulator (1-stop vs 2-stop)
- [ ] Dashboard with live data

## Data
Race data comes from the [FastF1](https://docs.fastf1.dev) library. The cache folder is not committed.

## Tools
Python, pandas, matplotlib, Jupyter, FastF1

## Notebooks
| Notebook | What it covers |
|----------|----------------|
| 01_race_overview | Loading one race, understanding the laps table, first lap time chart |

## Findings so far
- [Your observation from the first chart, e.g. what caused the biggest spike]
- [One thing that surprised you about the data]

## What I'm learning
- F1: stints, tyre compounds, undercut/overcut, safety car effects
- Data: pandas DataFrames, filtering, cleaning lap times

## Limitations
- Analysis is based on a single race so far, so conclusions don't generalise yet.

## Next steps
Clean out safety car and pit laps, then compare average pace per tyre compound.