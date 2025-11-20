🌤️ Weather Data Analysis — Exploratory Data Analysis (EDA)
This project performs Exploratory Data Analysis (EDA) on a multi-file global weather dataset containing information about temperature, humidity, pressure, wind, and weather conditions across different cities and timestamps.

The goal is to clean, prepare, and analyze the dataset to extract meaningful insights about seasonal patterns, temperature variations, and humidity trends.
✔️Problem Statement

Organizations that depend on environmental data—such as logistics, travel, and agriculture—require clear insights into how weather conditions change over time.
However, raw weather datasets are:

Spread across multiple CSV files

Contain missing values

Include inconsistent timestamps

Require merging city-wise attributes with measurements

This makes it difficult to directly understand:

Temperature trends over the year

Humidity seasonal behavior

Pressure stability

Wind patterns

Weather condition frequency

→ The problem: Extract actionable weather insights from complex, unstructured multi-file data.

✔️ Solution Approach

Using Python in Google Colab, we:

1. Collected & Combined Datasets

Loaded 7 CSV files: temperature, humidity, pressure, wind, weather description, and city attributes.

Standardized date formats.

Merged all datasets into a single clean dataframe.

Removed duplicates and handled missing values.

2. Data Cleaning Performed

Converted columns like timestamp → datetime.

Replaced or dropped missing sensor readings.

Checked for outliers in temperature and humidity.

Ensured all datasets aligned by city and datetime.

3. Exploratory Data Analysis (EDA)

We analyzed:

✔ Temperature patterns

Daily & monthly temperature trends

City-wise variations

Seasonal peaks and lows

✔ Humidity behavior

Identified seasonal humidity changes

Heatmap to understand time patterns

✔ Pressure & Wind

Compared pressure stability across cities

Observed wind speed variations

✔ Weather descriptions

Frequency count of weather conditions (Cloudy, Rain, Clear, etc.)

* Key Insights from the Analysis
🌡️ Temperature

Major cities showed a clear seasonal wave pattern

Hottest months: May–July

Coldest months: December–January

💧 Humidity

Humidity peaked during monsoon months

Dry months showed strong correlation with rising temperatures

🌬️ Wind

Wind speeds spiked particularly in coastal cities

Cities with mountains showed more directional variation

🌥️ Weather Condition Frequency

Most common conditions:

Clear sky

Scattered clouds

Light rain
