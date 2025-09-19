# SpaceX Launch Records Dashboard

A web-based dashboard that provides an interactive way to explore and analyze SpaceX launch data. This application is built with Python using the Dash and Plotly libraries.

## Features

*   **Launch Site Analysis:** View the total number of successful and failed launches for all sites or filter by a specific launch site using a dropdown menu.
*   **Payload Correlation:** Analyze the relationship between payload mass and launch success with an interactive scatter plot.
*   **Payload Filtering:** Use a range slider to filter the data based on payload mass (in kg).
*   **Booster Version Insights:** The scatter plot is color-coded by the booster version category, providing additional insights into the performance of different booster versions.

## How to Run

1.  Install the required Python libraries:
    ```bash
    pip install pandas dash plotly
    ```
2.  Run the application:
    ```bash
    python app.py
    ```
3.  Open your web browser and navigate to `http://127.0.0.1:8050/`.