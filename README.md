# Weather Data Analysis Project

## Overview
This project involves the analysis of a time-series weather dataset containing per-hour information about the weather conditions at a specific location. The dataset includes variables such as Temperature, Dew Point Temperature, Relative Humidity, Wind Speed, Visibility, Pressure, and Conditions.

## Dataset Description
The dataset comprises the following columns:
- **Temperature**: Recorded temperature at a specific hour.
- **Dew Point Temperature**: Temperature at which dew forms.
- **Relative Humidity**: Amount of moisture in the air relative to what the air can "hold" at that temperature.
- **Wind Speed**: Speed of the wind measured in km/h.
- **Visibility**: Distance one can clearly see.
- **Pressure**: Atmospheric pressure recorded in the dataset.
- **Conditions**: Description of the weather conditions.

## Analysis Performed
1. **Unique Wind Speed Values**: Identified all the unique wind speed values recorded in the dataset.
2. **Clear Weather Instances**: Counted the number of times when the weather was exactly 'Clear'.
3. **Specific Wind Speed Occurrences**: Determined the number of times when the wind speed was exactly 4 km/h.
4. **Handling Missing Values**: Identified and addressed all null (missing) values in the data.
5. **Mean Visibility**: Calculated the mean visibility.
6. **Pressure Standard Deviation**: Computed the standard deviation of the pressure data.
7. **Relative Humidity Variance**: Found the variance of relative humidity.
8. **Snow Instances**: Identified all instances when 'Snow' was recorded.

## Repository Structure
- **dataset/**: Directory containing the dataset files.
- **notebooks/**: Jupyter notebooks used for the analysis.
- **results/**: Directory for storing results of the analysis.
- **README.md**: Overview of the project and analysis performed (this file).

## Getting Started
To run the analysis:
1. Clone this repository.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the Jupyter notebooks or scripts in the `notebooks` and `scripts` directories.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.
