<a id="readme-top"></a>
<div align="center">
  <h1 align="center">F1 Race Debrief Analyzer</h1>
  <img 
    width="800" 
    alt="image" 
    src="https://github.com/user-attachments/assets/35fe38d0-007a-4f38-a4a4-6be1f48178a7" 
  />
</div>

## About the Project
Race-by-race strategy analysis using FastF1 API data.
Each notebook breaks down a single race, providing insights into lap times, tire strategy, and the pivotal decision that ultimately determined the race’s outcome.

## Races covered
- <a href="https://github.com/hai-henry/f1-race-debrief/blob/main/notebooks/2026/01_australia/australia_debrief.ipynb">Australian Grand Prix 2026</a>

## Setup
```bash
conda env create -f environment.yml
conda activate f1-debrief
```

## Note
>FastF1 caches session data locally on first load. Expect slow initial runs.
