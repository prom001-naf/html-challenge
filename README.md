# README: Mars News and Weather Scraping and Analysis Project

## Overview

This project demonstrates web scraping and data analysis skills by collecting and analyzing data from Mars-related websites. The project has two main deliverables:

1. **Scraping Titles and Preview Text from Mars News Articles**
2. **Scraping and Analyzing Mars Weather Data**

Through this project, insights into Martian weather patterns and trends are uncovered using Python libraries like Splinter, BeautifulSoup, Pandas, and Matplotlib.

---

## Deliverables

### **Deliverable 1: Scrape Titles and Preview Text from Mars News**
- Use Splinter and BeautifulSoup to automate browsing and extract data from the Mars News website.
- Extract titles and preview text for Mars news articles.
- Store the data in a list of dictionaries for further analysis.

### **Deliverable 2: Scrape and Analyze Mars Weather Data**
- Scrape Mars weather data from an HTML table on the Mars Weather website.
- Parse and clean the data, then store it in a Pandas DataFrame.
- Analyze the dataset to answer questions about Martian weather patterns, including:
  - Coldest and warmest months.
  - Months with the highest and lowest atmospheric pressure.
  - Estimating the length of a Martian year in terrestrial days.

---

## Technologies Used

- **Python**: For scripting and data processing.
- **Libraries**:
  - **Splinter**: For automated web browsing.
  - **BeautifulSoup**: For parsing HTML content.
  - **Pandas**: For data manipulation and analysis.
  - **Matplotlib**: For creating visualizations.

---

## How to Use

1. Clone the repository to your local machine.
2. Install the required Python libraries:
   ```bash
   pip install splinter beautifulsoup4 pandas matplotlib

# How to Run the Project

To successfully complete the project, follow these steps:

## Run the Jupyter Notebooks in the following order:

1. **part_1_mars_news.ipynb**  
   This notebook contains the code to scrape Mars news titles and preview text from the Mars News website.  
   - Navigate to the project directory in Jupyter Notebook.
   - Open and run the notebook step-by-step to collect and structure the Mars news data.

2. **part_2_mars_weather.ipynb**  
   This notebook contains the code to scrape, clean, and analyze Mars weather data from a simulated website.  
   - Open and run the notebook step-by-step to collect the weather data, perform analysis, and generate visualizations.

---

# Insights

### **Mars News**
- Extracted titles and summaries of Mars-related news articles, providing a valuable dataset for further research and analysis on Mars missions and findings.

### **Mars Weather**
- **Martian Months**: Identified 12 distinct Martian months based on the weather data.
- **Temperature Analysis**: Determined the coldest and warmest months on Mars, with Month 3 being the coldest and Month 8 being the warmest.
- **Pressure Analysis**: Found the months with the lowest and highest atmospheric pressure, with Month 6 having the lowest pressure and Month 9 the highest.
- **Martian Year Length**: Estimated the Martian year to be approximately **687 terrestrial days**, based on the periodic temperature trends observed.

---

# References

- **Mars News Website**  
  The news articles were sourced from a simulated Mars News website, operated by edX Boot Camps LLC for educational purposes.  
  Visit the real NASA Mars News page for more information: [NASA Mars News](https://mars.nasa.gov/news/).

- **Mars Weather Website**  
  The weather data table used for scraping and analysis was sourced from a simulated Mars Weather website designed for this project.

---

# Acknowledgments

This project was completed as part of the **Web Scraping and Data Analysis Module** in the edX Boot Camp curriculum. The resources provided by the curriculum, including instructional videos, guided exercises, and support from instructors and peers, were instrumental in the successful completion of this project.
