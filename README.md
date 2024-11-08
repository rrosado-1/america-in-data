# America in Data

## About this project
The idea is to track key metrics, events, legislature, etc happening on a Federal level with the US Government. 

### Brainstorm of things to track

#### Dynamically Provided Numbers using public APIs
- Inflation metrics
- Unemployment metrics
  - For inflation and unemployment the Bureu of Labor statistics provides a data API with public access to data
  - Should leverage this to gather accurate up to date numbers
  - https://data.bls.gov/timeseries/CUUR0000SA0
- Interest Rates
  - Can find the latest interest rate using the FRED API
  - Example query would be https://api.stlouisfed.org/fred/series/observations?series_id=DFEDTARL&api_key=YOUR_API_KEY&file_type=json

#### Possibly Manual Perdiodic / as necessary Updates
- Mortgage Rates
  - Is there a good official source to fetch these dynamically? 
- Noteworthy pieces of legislature
  - What is the best place to find latest information on federal legislative proceedings?
- Executive actions
  - Same as above, where would one find about this other than just the news? 
