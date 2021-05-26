# Stock-Market-Sector-Recovery-Analysis

[![Product Name Screen Shot][product-screenshot]](https://example.com)

## Project Demo

* [Bootstrap](https://getbootstrap.com)
* [JQuery](https://jquery.com)
* [Laravel](https://laravel.com)

## About The Project

The project aims to compare which sectors within the FTSE100 index recover and outperform the index in the aftermath of a market crash. 

The following are compared with each other during period of a market crash:
* Index -> Raw price performance of all stocks which make up FTSE 100
* Sector -> This represents overall raw price performance of stocks in a particular industry (e.g: tech, financial services etc) within the FTSE 100
* Individual stock -> Raw price performance of the individual stock within the sector

Market crash in a particular historical period is visualized for the above to visually identify which stocks outperform the index during aftermath of a crash.

Note: In order to measure true performance of a sector, I have simply used raw price performance of the stocks within the sector/industry to build the measure for comparison. We do have existing bespoke measures to track performance of sectors within an index, however, these do not reflect raw performance of individual stocks within the sector as the  performance measure is often skewed by elements such as Market cap etc.

## Libraries Used
* Pandas
* Ploty
* yfinance
* Numpy
