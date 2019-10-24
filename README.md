# rmd-example-state-profitability

An example `rmarkdown` report showcasing state KPIs for insurance policies.

## Files 

Scripts are named in the order in which they should be executed.

scripts/01_simulate_data.Rmd: creates dummy insurance data. For a real world analysis, this script would be replaced with code which queries real world data from a company's data warehouse or other data source.

scripts/02_EDA.Rmd: some basic exploratory analysis of the data. Although not used in the final report, it is useful to keep for reference.

scripts/03_state_report: final paramaterized report.

outputs/: directory containing outputs from 01_simulate_data.Rmd