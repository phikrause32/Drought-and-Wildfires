# Analyzing the Relationship Between Drought and Wild Fires in the US
This project looks at data on wildfire occurance points provided by the USDA in conjunction with data on drought levels provided by the US drought monitor. 

### Data Cleaning and Preparation
- Datasets were stripped to include only relevant variables, null values were eliminated, and categorical values were labelled
- Data on latitude and longitude were converted into GIS point values
- All GIS data was converted to correct coordinate reference system (CRS)
- State border geometries were intersected with a manufactured geometry to restrict mapping to the contiguous US
- Several joins/merges were used to integrate all data

### Mapping
- Overlayed maps of drought levels and fire occurances from were mapped at three years, all around 10 years apart
- Clear visual correlations between drought levels and number/severity of fires can be seen

### Quantitative Analysis
- Merged datasets to get county totals, then explored more quantitative relationships
- There are clear positiv corrleations between drought levels and number/severity of wildfires
- Additionally, a time series of total fires shows a sharp increase within the last two decades
