# Booking Agency Management System (Python)

A Python application that manages the operations of an **artist booking agency** —
cleaning and joining the agency's data (artists, agents, events), validating it,
and producing schedules and analytics.

> Coursework project: MTH766P *Programming in Python* (MSc, QMUL).

## What it does

- **Data cleaning & integration** — loads and reconciles multiple raw CSVs
  (artists, agents, active agents, events) into one cleaned dataset.
- **Validation** — uses regular expressions and type checks to catch malformed
  records (names, dates, identifiers).
- **Scheduling & analytics** — builds per-agent schedules and computes summary
  statistics over events and bookings.

## Files

| File | Contents |
|---|---|
| `MTH766P_Final_Project.ipynb` | Full solution notebook |
| `artists.csv`, `agents.csv`, `active_agents.csv`, `events.csv` | Raw inputs |
| `final_cleaned_data.csv` | Cleaned, integrated output |
| `agent0_schedule.txt` | Example generated schedule |

## Tech stack

Python · pandas · NumPy · `re` (regex validation) · datetime · Matplotlib

## Run

Open `MTH766P_Final_Project.ipynb` in Jupyter and run the cells in order; it
reads the CSVs, produces `final_cleaned_data.csv`, and generates the schedules
and plots.
