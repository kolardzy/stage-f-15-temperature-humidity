The CSV file includes an hourly/daily summary for [Szeged, Hungary](https://en.wikipedia.org/wiki/Szeged?oldformat=true) area, between 2006 and 2016.

This dataset was obtained from the Kaggle data science community. The CSV includes an hourly/daily summary for Szeged, Hungary between the year 2006- 2016.

The data set for our research project is obtained from the Kaggle data science community. The dataset contained 96,454 data entries.

Data available in the hourly response:

- time
- summary
- precipType
- temperature
- apparentTemperature
- humidity
- windSpeed
- windBearing
- visibility
- loudCover
- pressure

| Name | Type | Description |
| --- | --- | --- |
| Temp | Numeric, Continuous | Hourly temperature in a day measured in Celsius. |
| Apparent.Temp | Numeric, Continuous | Temperature that human perceive. Measured in Celsius |
| Summary | String, Categorical | Short summary of the current weather |
| Precip.Type | String, Categorical | Type of precipitation |
| Humidity | Numeric, Continuous | Level of humidity |
| Wind.Speed | Numeric, Continuous | Speed of the wind in km/h |
| Loud.Cover | Numeric, Categorical | Rating of the cover of cloud. This data seemed to be corrupted since there was only 1 label. |
| Pressure | Numeric, Continuous | Pressure measured in millibars |
| Daily.Summary | String, Categorical | Full summary at the current hour |
| Wind.Bearing.deg | Numeric, Continuous | Continuous Direction of the wind |
| Formatted.Date | String | Date and time the data entry was collected |
