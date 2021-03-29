HW5
================

This is a two - part homework. For HW 5, use the data from the [Johns
Hopkins Covid-19
Dashboard](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data#usa-daily-state-reports-csse_covid_19_daily_reports_us).

``` r
covid_data <- read_csv('https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports_us/03-27-2021.csv') 
```

    ## Parsed with column specification:
    ## cols(
    ##   Province_State = col_character(),
    ##   Country_Region = col_character(),
    ##   Last_Update = col_datetime(format = ""),
    ##   Lat = col_double(),
    ##   Long_ = col_double(),
    ##   Confirmed = col_double(),
    ##   Deaths = col_double(),
    ##   Recovered = col_logical(),
    ##   Active = col_logical(),
    ##   FIPS = col_double(),
    ##   Incident_Rate = col_double(),
    ##   Total_Test_Results = col_double(),
    ##   People_Hospitalized = col_logical(),
    ##   Case_Fatality_Ratio = col_double(),
    ##   UID = col_double(),
    ##   ISO3 = col_character(),
    ##   Testing_Rate = col_double(),
    ##   Hospitalization_Rate = col_logical()
    ## )

### Q1. (4 points)

Create a choropleth for COVID - 19 incidence rate

### Q2. (6 points)

Assess the spatial structure of the COVID-19 incidence rate. Include at
least a paragraph discussing your takeaway from this test.

### Q3. (1 point)

Project 2 will be due during the last week of class. Propose a dataset
to use for the project. This can either be areal data or point process
data. Note there will also be a presentation component for project 2.
