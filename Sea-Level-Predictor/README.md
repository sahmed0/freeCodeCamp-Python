# Sea Level Predictor
This project is the solution to the "Sea Level Predictor" challenge, the fifth project in the **freeCodeCamp Data Analysis with Python** certification.
It is a data analysis project that visualises the history of global sea level change and predicts future trends through 2050. 

## About The Project

This project uses historical data from the EPA (CSIRO Adjusted Sea Level) to analyse the rate of global sea level rise. It uses **Linear Regression** to predict sea levels in the year 2050.

To visualise the acceleration of sea level rise, the project plots two distinct prediction lines:
1.  **Historical Trend:** A line of best fit using all available data (1880–Present).
2.  **Recent Trend:** A line of best fit using only data from 2000 onwards, highlighting the increased rate of rise in recent decades.

## Sample Output

![Sea Level Plot](sea_level_plot.png)

## Technologies Used

* **Python**: Core programming language.
* **Pandas**: For data manipulation and CSV handling.
* **Matplotlib**: For data visualisation and plotting.
* **SciPy (linregress)**: For calculating the slope and intercept of the linear regression models.

## Project Structure

* `sea_level_predictor.py`: The main script containing the regression analysis and plotting logic.
* `test_module.py`: Unit tests to verify the accuracy of the plot elements and regression values.
* `epa-sea-level.csv`: Historical dataset containing sea level measurements.
* `README.md`: Project documentation.

### Prerequisites
Ensure you have Python installed. You will need the following libraries:

```bash
pip install pandas matplotlib scipy
```

## Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/sahmed0/Sea-Level-Predictor.git
    ```
2.  Navigate to the directory:
    ```bash
    cd Sea-Level-Predictor
    ```

## Usage

Ensure `epa-sea-level.csv` is in the working directory.

```python
import sea_level_predictor

# Generate and save the plot
sea_level_predictor.draw_plot()
```
