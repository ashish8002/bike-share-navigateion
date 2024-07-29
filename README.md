# Cyclistic Bike-Share Analysis

## Data Description

- **Location**: The data is in CSV format and is stored locally on my system.
- **Organization**: The data is comma-separated and organized with the following columns:
  - `ride_id`: Unique identifier for each ride.
  - `rideable_type`: Type of bike used.
  - `started_at`: Start date and time of the ride.
  - `ended_at`: End date and time of the ride.
  - `start_station_name`: Name of the station where the ride started.
  - `start_station_id`: ID of the station where the ride started.
  - `end_station_name`: Name of the station where the ride ended.
  - `end_station_id`: ID of the station where the ride ended.
  - `start_lat`: Latitude of the start station.
  - `start_lng`: Longitude of the start station.
  - `end_lat`: Latitude of the end station.
  - `end_lng`: Longitude of the end station.
  - `member_casual`: Indicates if the rider is a member or a casual rider.

## Issues with Bias or Credibility

- There are blanks in the `end_station_name`, `end_station_id`, `end_lat`, and `end_lng` columns, with about 99 missing values.
- `ride_id` has 12 incorrectly entered IDs that are not alphanumeric.

## Addressing Licensing, Privacy, Security, and Accessibility

- The dataset is a public dataset, so licensing is not a concern.
- Since the data is anonymized and does not contain personally identifiable information, privacy concerns are minimal.
- The data is stored securely on my local system with appropriate access controls.

## Verifying Data Integrity

- Data integrity was checked by validating the data types and ensuring there are no duplicates in `ride_id`.
- Missing values were identified and noted for further cleaning and preprocessing.

## Relevance to Research Question

- The dataset includes key variables such as ride start and end times, locations, and whether the rider is a member or casual, which are essential for understanding how annual members and casual riders use Cyclistic bikes differently.

## Problems with the Data

- Missing values in the `end_station_name`, `end_station_id`, `end_lat`, and `end_lng` columns.
- Incorrect entries in the `ride_id` column.

## Steps Taken

1. **Download and Store Data**: The data was downloaded and stored locally in a CSV file.
2. **Identify Organization**: The data is comma-separated and organized with appropriate headers.
3. **Sort and Filter Data**: Sorting and filtering were done to identify missing values and inconsistencies.
4. **Determine Credibility**: The credibility was assessed by checking for missing values and incorrect entries.

## Tools Chosen

1. I have chosen Microsoft Excel for this analysis due to its robust data manipulation capabilities, user-friendly interface, and powerful features for cleaning, sorting, and analyzing data. Excel is particularly suitable for handling CSV files, and its features such as filtering, conditional formatting, and pivot tables are highly effective for this type of exploratory data analysis.
2. For Vizualization Tablue has been choosen.

## Ensuring Data Integrity

- **Validating Data Types**: Ensuring that each column has the correct data type (e.g., dates in the date columns, numeric values for latitudes and longitudes).
- **Checking for Duplicates**: Ensuring that `ride_id` values are unique to avoid duplicate records.
- **Handling Missing Values**: Identifying and documenting missing values for further action.

## Steps to Ensure Data Cleanliness

1. **Identifying Missing Values**: Checked columns for missing values, particularly `end_station_name`, `end_station_id`, `end_lat`, and `end_lng`.
2. **Correcting Incorrect Entries**: Identified non-alphanumeric `ride_id` entries and marked them for correction or removal.
3. **Consistency Checks**: Ensured consistency in data entries, such as station names and IDs.

## Verifying Data Cleanliness

1. **Use Conditional Formatting**: Highlight missing or incorrect values to ensure all data points are accounted for.
2. **Data Validation**: Apply data validation rules to columns to ensure only valid data is entered.
3. **Summary Statistics**: Generate summary statistics to ensure that the data falls within expected ranges and distributions.
4. **Error Checking Tools**: Utilize Excel’s built-in error checking tools to identify and correct anomalies.

## Documentation of Cleaning Process

1. **Initial Data Review**: Conducted a preliminary review to identify key issues such as missing values and incorrect entries.
2. **Data Validation**: Applied data validation and conditional formatting to identify and correct errors.
3. **Correction and Imputation**: Addressed missing values by either imputing them where possible or flagging them for further investigation.
4. **Final Verification**: Verified the final dataset to ensure that all identified issues were addressed.

## Conclusion

This README provides an overview of the dataset, the issues identified, and the steps taken to clean and prepare the data for analysis. The cleaned dataset is now ready for further exploration and analysis to gain insights into Cyclistic bike usage patterns.
