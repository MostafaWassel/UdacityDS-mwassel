# World Bank Data Analysis Project

## Motivation
This project analyzes World Bank data to understand global economic trends and relationships between GDP, population growth, and educational attainment across countries. The analysis aims to answer the following questions:

1. How does GDP distribution vary across countries and what are the major disparities?
2. Is there a relationship between GDP levels and population growth rates?
3. How have country GDP rankings changed over time (2000-2015)?
4. Can we predict a country's GDP using historical data and demographic indicators?

## Libraries Used
The following Python libraries were used in this analysis:
- pandas (1.5.3): Data manipulation and analysis
- numpy (1.24.2): Numerical computations
- matplotlib (3.7.1): Basic plotting and visualization
- seaborn (0.12.2): Advanced statistical visualizations
- scikit-learn (1.2.2): Machine learning algorithms and metrics

To install the required libraries, run:
```bash
pip install -r requirements.txt
```

## Files in the Repository
- `Course1Project.ipynb`: Main Jupyter notebook containing the analysis
- `WBData/WBData.csv`: World Bank dataset with GDP, population, and education metrics
- `requirements.txt`: List of Python dependencies
- `README.md`: Project documentation (this file)

## Project Structure
The analysis follows the CRISP-DM methodology:
1. Business Understanding: Define objectives and success criteria
2. Data Understanding: Load and examine World Bank dataset
3. Data Preparation: Clean and transform data for analysis
4. Data Analysis: Investigate GDP distribution and relationships
5. Modeling: Build and evaluate GDP prediction model
6. Deployment: Example prediction application

## Summary of Results
Key findings from the analysis:
1. Significant economic disparities exist between countries
2. Higher GDP countries tend to have lower population growth rates
3. Achieved 99% accuracy in GDP predictions using historical data

For a detailed discussion of the results, please read our [blog post]([link-to-blog-post](https://medium.com/@mostafa.wassel.dio/unlocking-economic-insights-predicting-gdp-with-world-bank-data-historically-2000-2015-99265dd03898)).

## Future Improvements
Potential enhancements for future work:
1. Include additional economic indicators
2. Extend analysis to more recent years
3. Explore regional patterns and clustering
4. Incorporate more advanced prediction methods

## Setup Instructions
1. Clone this repository:
```bash
git clone https://github.com/yourusername/world-bank-analysis.git
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run Jupyter Notebook:
```bash
jupyter notebook Course1Project.ipynb
```

## Acknowledgements
- World Bank for providing the open dataset
- Udacity Data Science Nanodegree Program for project guidance
- [World Bank Data Documentation](https://datahelpdesk.worldbank.org/) for metadata and definitions
- scikit-learn documentation for model implementation references

## Author
Moustafa Wassel

