# UN Data Exploration: Gross Domestic Product and Internet Usage

## Description
This project explores the relationship between Gross Domestic Product (GDP) per capita and internet usage across various countries using data from the United Nations. The analysis aims to uncover trends, visualize data distributions, and understand how GDP per capita and internet usage have evolved over time.

## Table of Contents
1. [Description](#description)
2. [Data Sources](#data-sources)
3. [Project Structure](#project-structure)
4. [Installation and Setup](#installation-and-setup)
5. [Usage](#usage)
6. [Analysis](#analysis)
7. [Key Findings](#key-findings)
8. [Contributing](#contributing)
9. [Contact Information](#contact-information)

## Data Sources
- **Gross Domestic Product (GDP) per capita**: [UN Data](http://data.un.org/Data.aspx?d=WDI&f=Indicator_Code%3aNY.GDP.PCAP.PP.KD)
- Percentage of Individuals using the Internet: [UN Data](http://data.un.org/Data.aspx?d=ITU&f=ind1Code%3aI99H)

## Project Structure
```
un-data-exploration/
├── data/
│   ├── gdp_percapita.csv
│   ├── internet_use.csv
├── notebooks/
│   ├── UN_Data_Exploration.ipynb
├── README.md
└── .gitignore
```

## Installation and Setup
To run this project locally, you'll need to follow these steps:

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-username/un-data-exploration.git
   cd un-data-exploration
   ```

2. **Create and Activate a Virtual Environment** (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the Required Packages**:
   ```sh
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. **Launch Jupyter Notebook**:
   ```sh
   jupyter notebook
   ```

5. **Open the Notebook**:
   - Navigate to the `notebooks` folder and open `UN_Data_Exploration.ipynb`.

## Usage
The Jupyter Notebook contains all the steps for data loading, cleaning, analysis, and visualization. Follow the instructions in the notebook cells to perform the analysis.

## Analysis
The analysis includes the following steps:

1. **Data Loading**: Importing the GDP and internet usage datasets.
2. **Data Cleaning**: Dropping unnecessary columns and renaming columns for clarity.
3. **Exploratory Data Analysis (EDA)**: 
   - Distribution of GDP per capita for the year 2020.
   - Comparison of GDP per capita across different decades.
   - Identification of countries with significant GDP changes.
4. **Visualizations**: Creating various plots (histograms, density plots, boxplots, violin plots, scatterplots) to visualize data distributions and trends.
5. **Merging Datasets**: Combining GDP and internet usage data to analyze the relationship between the two.

## Key Findings
- **Distribution of GDP**: The GDP per capita distribution varies widely among countries, with some outliers having extremely high values.
- **Trends Over Time**: Most countries have shown an increase in GDP per capita from 1990 to 2020, although a few have experienced a decline.
- **Internet Usage**: The percentage of internet users has increased significantly over the years, with some countries having near-universal internet access by 2014.
- **Correlation**: There is a noticeable correlation between higher GDP per capita and higher internet usage, although some exceptions exist.

## Contributing
If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Contact Information
For any questions or inquiries, please contact [Muhammedismael2121@gmail.com](mailto:Muhammedismael2121@gmail.com).

