# Stock-Market-Sector-Recovery-Analysis

> Inspired by 2020 Covid market crash

![Example Comparision ScreenShot](https://github.com/Naharul98/Stock-Market-Crash-Recovery-Analysis/blob/main/Screenshots/Sample-comparison.jpg?raw=true)

## Project Demo

* [Data Retrieval and Preprocessing](https://nbviewer.jupyter.org/github/Naharul98/Stock-Market-Crash-Recovery-Analysis/blob/main/Data-Retrieval-And-Preprocessing.ipynb)
* [Visualization of performance comparision between all sectors within FTSE 100](https://nbviewer.jupyter.org/github/Naharul98/Stock-Market-Crash-Recovery-Analysis/blob/main/Visualization-of-Performance-comparison---sector-to-index---during-crash.ipynb)
* [Performance comparision at peak of crash](https://nbviewer.jupyter.org/github/Naharul98/Stock-Market-Crash-Recovery-Analysis/blob/main/Performance-of-stocks-at-peak-of-crash-relative-to-index.ipynb)
* [Performance comparison of any given individual sector within FTSE100](https://nbviewer.jupyter.org/github/Naharul98/Stock-Market-Crash-Recovery-Analysis/blob/main/Performance-comparison-of-individual-sector-to-index.ipynb)


## About The Project

The project aims to compare which sectors within the FTSE100 index recover and outperform the index in the aftermath of a market crash. 

The following are compared with each other during period of a market crash:
* Index -> Raw price performance of all stocks which make up FTSE 100
* Sector -> This represents overall raw price performance of a particular industry (e.g: tech, financial services etc) within the FTSE 100
* Individual stock -> Raw price performance of the individual stock within the sector

Market crash in a particular historical period is visualized for the above to visually identify which stocks outperform the index during aftermath of a crash.

Note: In order to measure true performance of a sector, I have simply used raw price performance of the stocks within the sector/industry to build the measure for comparison. We do have existing bespoke measures to track performance of sectors within an index, however, these do not reflect raw performance of individual stocks within the sector as the  performance measure is often skewed by elements such as Market cap etc.

## Libraries Used
* Pandas
* Ploty
* yfinance
* Numpy
