# gold-price-analysis

Dashboard for gold prices over time (updated daily)

## Chart 1: Time-series plots: (from 1979)
1) Daily Gold Price
2) One-day differences
3) Seven-day differences
4) 30-day differences

## Chart 2: Rolling correlation with yields of Treasury bills, notes and bonds. 
See: https://www.springer.com/cda/content/document/cda_downloaddocument/9780387279657-c1.pdf?SGWID=0-0-45-169676-p59330694 for an explanation of rolling correlation for forecasting.

## Steps to run app:
Copy the following into an R console/Rstudio and press ENTER:
>> runGitHub( “daily-gold-price”, "kalyani-subbiah") >>
Or copy the following into an R console/Rstudio and press ENTER:
>> runGist("63e9b4194eb2889645666120c95a258c") >>

**Data sources**: Quandl APIs from World Gold Council and US Treasury. 

Ongoing. 

To be added:
Rolling correlation with spot exchange rates of four largest gold consumers: China, India, US, Germany.
