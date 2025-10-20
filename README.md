# Seattle weather project

This project explores and compares rainfall patterns between Seattle, Washington and Miami, Florida using real weather data. While Seattle is often known for its frequent drizzle and cloudy days, Miami experiences tropical rainstorms and a humid climate. Using data science methods, this project analyzes precipitation trends to determine which city actually receives more rain and how rainfall varies throughout the year. Visualizations and statistical tests are used to support the findings and provide insights into each city’s unique weather characteristics.

---

## Project Overview

- **Objective:** Rainfall comparison between the cities Seattle, WA and Miami, FL.
- **Domain:** Weather
- **Key Techniques:** Exploratory data analysis

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** https://github.com/prithika029/weather/tree/main/data
- **Description:** Brief overview of the dataset features, size, and format
- **License:** (if applicable)

---

## Analysis

The analysis was performed using jupyter notebooks that process and visualize rainfall data from Seattle, WA and Miami, FL for the period 2018–2022. 

The below steps are followed as part of analysis.

Ensure all dates are present, filling in missing dates where necessary and handle missing precipitation values.
Calculate monthly mean, and medians of precipitation.
Calculate the proportion of days with rainfall for each month.
Create box plots to examine monthly precipitation distributions.
Generate bar plots showing mean precipitation for each month with error bars.
Plot the proportion of days with rainfall per month, marking significant differences with star symbols.
Perform tests to identify months with significant differences in precipitation patterns between Seattle and Miami.

---

## Results

The result shows clear seasonal differences between the two cities. Seattle experiences rain more frequently throughout most of the year, especially during the fall and winter months (October–March). Miami, on the other hand, receives less frequent rain overall but has a noticeable increase during the summer months (June–September) due to its tropical climate and hurricane season. Overall, Seattle has more rainy days, while Miami tends to have heavier rainfall concentrated in fewer months.

---

## Authors

- Prithika Kandasamy - https://github.com/prithika029

---

## License
This project is licensed under the MIT License - see the LICENSE file for details.
---

## Acknowledgements

- Tools/libraries used 
	Tool : Jupyter notebook 
	Libraries : pandas, numpy, matplotlib, pyplot, seaborn
- Tutorials or papers referenced - https://stackoverflow.com/questions/19324453/add-missing-dates-to-pandas-dataframe
- Inspiration or collaborators - https://github.com/brian-fischer/DATA-5100/tree/main/weather
