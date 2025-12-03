# AQI-Analysis: Air Quality Index Monitoring and Prediction

## 📜 Description

The Air Quality Index (AQI) is a critical measure of air cleanliness and its impact on human health. This repository is dedicated to the **analysis, visualization, and prediction** of Air Quality Index data.

Air is essential for life, and understanding its quality is of immense importance to our well-being. This project aims to extract meaningful insights from historical and real-time air quality data using data science and machine learning techniques.

---

## ✨ Features and Analysis

This project primarily consists of two Jupyter Notebooks that perform distinct stages of the analysis:

1.  **Exploratory Data Analysis (EDA):**
    * Cleaning and preprocessing raw air quality datasets.
    * Visualizing trends, seasonality, and correlations between pollutants (e.g., PM2.5, NO2, O3, CO) and the overall AQI.
    * Generating statistical summaries for key air quality metrics. (`aqi_analysis.ipynb`)
2.  **Machine Learning (ML) Modeling:**
    * Developing predictive models (e.g., Regression, Time Series) to forecast future AQI values.
    * Training models using various features like pollutant concentrations and time-based factors.
    * Model evaluation and performance metrics. (`ML.ipynb`)

---

## 💻 Technologies and Libraries

The project is built entirely within the **Jupyter Notebook** environment, primarily using **Python** and its ecosystem of data science libraries:

* **Language:** Python
* **Environment:** Jupyter Notebook
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn, (potentially) TensorFlow/Keras

---

## 🗃️ Data Sources

The analysis utilizes a combination of publicly available and specific location-based datasets:

* **`air quality data.csv`**: A primary, general dataset for initial analysis and model training.
* **`Milan_Air_Quality.json`**: A specific dataset focusing on air quality data for the city of **Milan**.
* **`Data/`**: A folder intended to store raw, processed, or intermediate data files.
* **`API_keys.json`**: Indicates that the project uses APIs for data retrieval, likely to fetch the latest or real-time AQI information.

---

## 🛠️ Setup and Installation

To get a local copy of this project up and running, follow these steps:

### Prerequisites

You need to have Python and the necessary libraries installed. A good starting point is the **Anaconda** distribution, which includes Python and Jupyter Notebook.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Star-nikki/AQI-Analysis.git](https://github.com/Star-nikki/AQI-Analysis.git)
    cd AQI-Analysis
    ```

2.  **Set up the environment:**
    It is highly recommended to create and activate a virtual environment.
    ```bash
    # Create a virtual environment (e.g., named 'aqi_env')
    conda create --name aqi_env python=3.9
    conda activate aqi_env
    ```

3.  **Install dependencies:**
    *(Assuming a standard set of data science libraries)*
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```
    *Note: If you encounter issues, check the notebook files for any specific, non-standard library imports.*

4.  **Configure API Keys (If needed):**
    If the project relies on active API calls, you must fill in the necessary keys in the `API_keys.json` file.

---

## 🚀 Usage

To explore the analysis and models, launch the Jupyter Notebook environment:

```bash
jupyter notebook
