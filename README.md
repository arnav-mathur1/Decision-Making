# Decision-Making Data Visualizations

Project completed through the Science and Engineering Apprenticeship Program (SEAP) at the U.S. Naval Research Laboratory (NRL) in Summer 2022.

Conducted under [Dr. Mark A. Livingston](https://scholar.google.com/citations?user=PuuyAu0AAAAJ&hl=en).

## Overview

This project explored how high-dimensional gameplay decision data could be organized and visualized to make patterns in sequential decision-making easier to understand.

The work focused on creating and transforming gameplay-style datasets, generating controlled synthetic decision data, and comparing visualization methods for showing how choices change across a sequence. The main techniques explored were parallel coordinates, parallel sets / parallel categories, and stream graphs.

## What I Did

- Created and modified datasets representing sequences of gameplay decisions
- Processed, cleaned, filtered, and reshaped data using Python and Pandas
- Generated synthetic decision data with controlled probability distributions
- Worked with both small collected gameplay datasets and larger external datasets
- Built interactive visualizations with Plotly and static visualizations with Matplotlib
- Compared parallel coordinates, parallel sets / parallel categories, stream graphs, scatter plots, and bar charts
- Used filtering and scenario selection to make large decision datasets easier to interpret
- Tested whether known changes in decision probabilities were visible in the resulting plots

## Main Result

Parallel sets / Plotly parallel categories were the most useful visualization for discrete decision sequences. They made it possible to see how frequently choices occurred, how choices connected across multiple stages, and how filtering to a specific scenario made large datasets easier to interpret.

Controlled grid experiments also showed that increasing the probability of a specific action produced visibly wider bands in the parallel-set visualization.

## Tools

Python, Pandas, Plotly, Matplotlib, Jupyter Notebook

## Running the Notebooks

The project was developed in Jupyter Notebook using Python. Most notebooks expect their associated CSV files to be available in the same project directory or referenced subdirectory.

The files are unorganized. With the help of Codex, I was able to summarize the files in a 'files.md' to show the progression of research.

## Follow-Up

As a follow-up to working at SEAP through the NRL, I participated in the [Naval Horizons Essay Contest](https://www.navalhorizons.us/) twice, which is sponsored by Naval STEM for the Department of the Navy.

I [wrote](https://docs.google.com/document/d/1tZ2bl0REcZsCtO7UHAyz4p-rhpobsiFeAVmVeFt5__w/edit?usp=sharing) about my interest in AI/ML for intelligent autonomous systems through predictive modeling and digital twins. Even though I wrote the essays almost 4 years ago, the issues still interest me today.
