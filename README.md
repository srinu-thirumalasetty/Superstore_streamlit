
# Superstore Data Analysis Dashboard
An interactive data analysis dashboard built using Python and Streamlit to explore and visualize Superstore sales, profit, quantity, discounts, shipping modes, customers, cities and states.
## Project Overview
This project analyzes the Superstore dataset using interactive data visualizations and aggregation techniques. Users can select different categories and metrics to explore business performance and gain insights from the data.
## Features
- **Top Profitable Cities and States:** Identify cities and states with the highest profits.
- **Ship Mode Analysis:** Analyze Sales, Profit, Quantity and Discount across different shipping modes.
- **Profit Analysis:** Aggregate profit across various dimensions such as Region, Segment, City, Category and Product.
- **Discount Analysis:** Explore the relationship between discounts and Sales, Profit or Quantity.
- **Category and Sub-Category Analysis:** Compare sales and profit across product categories.
- **Customer Analysis:** Explore top customers based on selected metrics.
- **Order Count Analysis:** Compare order counts across cities and states.
- **Interactive Visualizations:** Explore results through charts and tables using Streamlit and Plotly.
## Technologies Used
- Python
- Streamlit
- Pandas
- Plotly
- Excel
## Dataset
The project uses SSStore3.xlsx, an Excel dataset containing Superstore sales-related data.
## How to Run
Clone the repository:
```bash
git clone https://github.com/srinu-thirumalasetty/Superstore_streamlit.git
```
Navigate to the project folder:
```bash
cd Superstore_streamlit
```
Install the required dependencies:
```bash
pip install -r requirements.txt
```
Run the application:
```bash
streamlit run "1_to_8 merged.py"
```
## Project Structure
- `1_to_8 merged.py` – Combined Streamlit application containing the analyses.
- `SSStore3.xlsx` – Dataset used by the application.
- `st_1.py to st_8.py` – Individual analysis scripts and sections.
## Project Purpose
This project was developed to practice Python-based data analysis, data aggregation, interactive visualization and building dashboards using Streamlit.
