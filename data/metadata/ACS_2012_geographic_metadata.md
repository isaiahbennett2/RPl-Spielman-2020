- `Title`: American Community Survey 2012 5-year Estimate Demographic Variables
- `Abstract`: The 5-year ACS provides estimates surrounding demographic information in the USA. These estimates are more reliable than 1-year and 3-year estimates but less reliable than decennial census data. On the other hand, 5-year estimates are less current than 1-year and 3-year estimates because they represent measurements taken over 60 months. See the [census website](https://www.census.gov/programs-surveys/acs/guidance/estimates.html) for more details.
- `Spatial Coverage`: United States, excluding Puerto Rico
- `Spatial Resolution`: County and county-equivalents
- `Spatial Reference System`: None, just attribute data
- `Temporal Coverage`: 2008-2012
- `Temporal Resolution`: Data averaged over five years
- `Lineage`: Original data downloaded from Social Explorer and then placed in the original study's GitHub repository: https://github.com/geoss/sovi-validity. Reproduction data obtained directly from the census via API.
- `Distribution`: The reproduction data is distributed via a census API. See the detailed tables on the [census website](https://www.census.gov/data/developers/data-sets/acs-5year/2012.html) and instructions for drawing census data directly into python on the [pygris website](https://walker-data.com/pygris/). Spielman et al. originally accessed the ACS data with Social Explorer from the following two tables.
  - http://www.socialexplorer.com/pub/reportdata/HtmlResults.aspx?reportid=R10728365
  - http://www.socialexplorer.com/pub/reportdata/HtmlResults.aspx?reportid=R10775556
- `Constraints`: Census data is available in the public domain
- `Data Quality`: Margin of error provided by the Census Bureau for relevant variables
- `Variables`:  See ACS_2012_data_dictionary.csv