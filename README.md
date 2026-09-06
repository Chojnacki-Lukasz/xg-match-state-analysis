# Match State xG Analysis & Wingback Scouting Methodology ⚽📊

This repository contains an analytical project focused on processing StatsBomb event data to evaluate team performance contexts and establish a scouting framework for a wingback position. 

Projekt zrealizowany w ramach zadań analitycznych (Pogoń Grodzisk Mazowiecki vs Polonia Bytom), obejmujący czyszczenie danych, inżynierię cech oraz raportowanie taktyczne.

##  Tech Stack
* **Python** (Pandas)
* **Jupyter Notebook**
* **Data Source:** StatsBomb Event Data

##  Project Scope

### 1. Dynamic xG Calculation by Match State
A Python algorithm designed to dynamically track the match score before every event and calculate Expected Goals (xG) created (xGF) and conceded (xGA) based on the current match state (Winning, Drawing, Losing).
* Tracks sequential outcomes to correctly attribute goals to the pre-shot match state.
* Aggregates threat creation metrics to identify periods of dominance.

### 2. Wingback Scouting Framework
A theoretical methodology translating tactical requirements into data-driven scouting metrics using StatsBomb data:
* **On-ball Value:** Expected Assists (xA), progressive passes, and dribble success rates.
* **Defensive Output:** Duel win probability and counterpressing actions in transition.
* **Spatial Profiling:** Activity heatmaps and defensive intervention geometries.
* **Limitations:** Acknowledgement of event-data blind spots (e.g., off-ball movement, physical intensity) requiring supplementary video analysis.

##  Author
**Łukasz Chojnacki**
Applied Mathematics & Data Analysis
