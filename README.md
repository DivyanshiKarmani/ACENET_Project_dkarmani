# Weekly Task & Habit Tracker

## Overview
This project implements a command-line Python application to track weekly tasks and daily habits. Users can add, mark complete, remove tasks and habits, and generate daily or weekly reports.

## Usage
- Run the Jupyter notebook (`habit_tracker.ipynb`) to interact via the main menu.
- For HPC batch processing, run the Python script (`DKarmani_Project-HPC-template.py`) which processes multiple data files (`dictionaries_1` to `dictionaries_10`).
- Submit the job on the HPC cluster with the provided job script (`submit_job.sh`).

## Files
- `habit_tracker.ipynb`: Interactive notebook with full functionality.
- `DKarmani_Project-HPC-template.py`: Python script adapted for batch processing on HPC.
- `dictionaries_1` to `dictionaries_10`: Sample data files.
- `submit_job.sh`: HPC job submission script.

## Requirements
- Python 3.x
- asteval library (installed in virtual environment on HPC)
- Jupyter for notebook usage

## HPC Instructions
1. Transfer files to HPC cluster.
2. Activate the Python virtual environment.
3. Submit job script using `sbatch submit_job.sh`.
4. Monitor job status with `squeue` and resource usage with `seff`.
