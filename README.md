# Dataset README

## Description
This dataset comprises various files related to Sydney's water temperature, humidity, and air quality. The data is sourced from different sources and processed to provide insights into environmental conditions.

## Data Sources
- **Sydney Water Temperature and Humidity (30-minute Aggregation)**:
  - URL: [Sydney Water Temperature and Humidity Dataset](https://data.penrith.city/api/explore/v2.1/catalog/datasets/sydney-water-temperature-and-humidity-30mn-aggregation-2022/exports/csv?lang=en&timezone=Australia%2FSydney&use_labels=true&delimiter=%2C)
  - Description: This dataset contains raw data for Sydney's water temperature and humidity, collected at 30-minute intervals. The data is programmatically downloadable from the provided URL.

- **Hourly Average PM Data**:
  - Source: AQMS (Air Quality Monitoring System) website
  - Description: Raw data for hourly average particulate matter (PM) concentrations, manually downloaded from the AQMS website.

## Files
- **sydney_water_temp_hum_v0.csv**:
  - Description: Raw data for water temperature and humidity in Sydney, programmatically downloaded via the provided URL and saved locally.

- **hourly_avg_pm_v0.csv**:
  - Description: Raw data for hourly average PM concentrations, manually downloaded from the AQMS website.

- **\*_v1.csv**:
  - Description: Files with column names reformatted against their respective \*_v0.csv files.

- **\*_v2.csv**:
  - Description: Cleaned datasets derived from \*_v1.csv files.

- **\*_v3.csv**:
  - Description: Merged file containing data from all \*_v2.csv files.

## Usage
- The raw data files (\*_v0.csv) can be used for initial exploration and analysis.
- Use the files with suffix \*_v1.csv for datasets with reformatted column names.
- Cleaned datasets are available in files with suffix \*_v2.csv.
- The merged dataset with data from all cleaned files is stored in \*_v3.csv.

## License
Please refer to the respective data sources for licensing information.

## Contact
For any inquiries or issues regarding the dataset, please contact [insert contact information].
```

Feel free to customize it further as needed!
