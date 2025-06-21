# Automobile Sales Statistics Dashboard

This project is a Dash-based interactive web application for analyzing and visualizing automobile sales data. The dashboard provides users with insights into yearly automobile statistics and statistics specific to recession periods.

---

<img src="https://github.com/vinay124-tech/Automobile-Sales-Statistics-Dashboard/blob/main/Results/Recession_Period_Statistics.jpeg?raw=true" alt="Alt text" width="500" height="300"> <img src="https://github.com/vinay124-tech/Automobile-Sales-Statistics-Dashboard/blob/main/Results/Total%20expenditure%20share%20by%20vehicle%20type%20during%20recessions.png?raw=true" alt="Alt text" width="500" height="300"> 


## Features

1. **Dropdown Menu for Statistics Selection**
   - Yearly Statistics
   - Recession Period Statistics

2. **Yearly Statistics**
   - Yearly average automobile sales visualized using a line chart.
   - Monthly total automobile sales using a line chart.
   - Average number of vehicles sold by vehicle type using a bar chart.
   - Total advertisement expenditure for each vehicle type using a pie chart.

3. **Recession Period Statistics**
   - Average automobile sales fluctuations during recession periods visualized using a line chart.
   - Average number of vehicles sold by vehicle type using a bar chart.
   - Total advertisement expenditure share by vehicle type using a pie chart.
   - Effect of unemployment rate on vehicle type and sales visualized using a grouped bar chart.

4. **Interactivity**
   - Dynamically update charts based on user-selected statistics.
   - Year dropdown menu is enabled only when "Yearly Statistics" is selected.

---

## Requirements

- Python 3.8+
- Dash 2.0+
- Pandas
- Plotly

---

## Installation

1. Clone this repository.
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install required dependencies.
   ```bash
   pip install dash pandas plotly
   ```

3. Run the app.
   ```bash
   python app.py
   ```

4. Open the app in a web browser.
   ```
   http://127.0.0.1:8050/
   ```

---

## Data Source

The data used in this project is available at the following URL:

[Historical Automobile Sales Data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/historical_automobile_sales.csv)

---

## File Structure

- `app.py`: The main Python script containing the Dash app implementation.

---

## How It Works

1. **Dropdown Menus**:
   - Users select either "Yearly Statistics" or "Recession Period Statistics" from the first dropdown menu.
   - If "Yearly Statistics" is selected, the year dropdown menu is enabled for year-specific data visualization.

2. **Callbacks**:
   - Dynamic interaction between user inputs and chart outputs is handled by Dash callbacks.
   - Based on the selected statistic type and year, appropriate visualizations are rendered in the output container.

3. **Visualizations**:
   - The app uses Plotly to generate interactive charts, including line charts, bar charts, and pie charts.

---

## Dashboard Layout

- **Title**: Center-aligned title at the top of the dashboard.
- **Dropdown Menus**: Positioned below the title for selecting statistics type and year.
- **Charts**: Arranged in a grid layout to display visualizations interactively.

---

## Example Usage

1. Start the application.
2. Select "Yearly Statistics" and choose a specific year to explore automobile sales and advertisement expenditure trends for that year.
3. Select "Recession Period Statistics" to analyze sales trends and advertising expenditure during economic recessions.

---

## Improvements

- Add more filters (e.g., region, manufacturer).
- Include detailed tooltips for each chart.
- Enhance styling and layout for better user experience.
- Integrate a database for dynamic data updates.

---

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

