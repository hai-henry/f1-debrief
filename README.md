# F1 Race Debrief Analyzer
<div align="center">
  <img 
    width="800" 
    alt="image" 
    src="https://github.com/user-attachments/assets/35fe38d0-007a-4f38-a4a4-6be1f48178a7" 
  />
</div>

Race-by-race strategy analysis using FastF1 API data.
Each notebook breaks down a single race, providing insights into lap times, tire strategy, and the pivotal decision that ultimately determined the race’s outcome.

## Races covered
- Australian Grand Prix 2026

## Setup
```bash
conda env create -f environment.yml
conda activate f1-debrief
```

## Note
>FastF1 caches session data locally on first load. Expect slow initial runs.
