# INST414-Soccer-Rivalry-Network

This repository contains the code and data for my INST414 network analysis project.

## Project Question

Which English soccer clubs occupy the most important positions in an online network created from hyperlinks in Wikipedia rivalry sections?

## Network Definition

- Nodes represent English professional soccer club Wikipedia pages.
- Directed edges represent hyperlinks from one club's rivalry section to another club's Wikipedia page.

## Analysis

The project uses NetworkX to calculate:

- In-Degree Centrality
- Betweenness Centrality
- PageRank

The analysis identified Chelsea, Manchester United, and Arsenal as the three highest-ranked clubs by PageRank in the collected network.

## Files

- `soccer_rivalry_links.csv` - collected rivalry hyperlink data
- `soccer_rivalry_results.csv` - centrality results
- `soccer_rivalry_network.png` - network visualization
- `soccer_rivalry_pagerank.png` - PageRank chart
- `.ipynb` notebook - Python analysis
