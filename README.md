# Sales and Customers Dashboard

## Overview
The **Sales and Customers Dashboard** is an interactive Tableau dashboard designed to provide comprehensive insights into sales performance and customer metrics. In today's data-driven business environment, access to real-time insights is crucial for making informed decisions. This dashboard addresses key challenges faced by organizations by consolidating complex data into an intuitive interface, enabling users to analyze sales trends, customer distribution, and profitability across various dimensions.

### Key Challenges Addressed
- **Lack of Visibility**: Organizations often struggle to obtain a clear view of their sales performance across multiple metrics. This dashboard consolidates data into a single interface for easy monitoring.
- **Inefficient Data Analysis**: Manual analysis of sales data can be time-consuming and error-prone. The dashboard automates this process, providing instant visualizations that highlight trends and patterns.
- **Inability to Track Customer Behavior**: Understanding customer preferences is essential for tailoring marketing strategies. This dashboard offers insights into customer distribution and purchasing patterns.
- **Difficulty in Historical Comparison**: Evaluating current performance against historical data is vital for identifying growth opportunities. The dashboard facilitates this comparison through dynamic visualizations.

## ERD Diagram
![sales custERD](https://github.com/user-attachments/assets/30253a61-55c1-41a8-abc9-9bc2922b5076)



## Functionality
The dashboard includes various functionalities that enhance user experience and analytical capabilities:
- **Interactive Visualizations**: Users can engage with various charts and graphs to explore data from multiple angles, fostering deeper insights into sales trends and customer behavior.
- **Dynamic Filters**: Users can apply filters based on year, category, subcategory, region, state, or city, enabling tailored analyses that focus on the most relevant data.
- **Navigation Buttons**: The dashboard features easy-to-use navigation buttons that allow users to seamlessly switch between the Sales and Customers dashboards.

## Improved Features List

### 1. Bans
- **Description**: Displays key metrics such as Total Sales, Total Profit, Total Quantity, Total Customers Count, Total Sales per Customer, and Total Orders Count at the top of the dashboard.
- **Unique Feature**: Each ban includes a percentage difference indicator compared to the previous year, with arrow symbols indicating whether values have risen or fallen.

### 2. Sparkline Charts
- **Description**: Compact visualizations of monthly trends in sales, profit, and quantity attached to their respective bans for immediate context.
- **Advanced Feature**: Dual axes compare current year performance against previous year metrics while highlighting the highest and lowest months with circles.

### 3. Bar in Bar Chart
- **Description**: Compares current year (CY) sales against previous year (PY) sales for each subcategory.
- **Tooltip Information**: Hovering over bars reveals detailed tooltips showing sub-category name, CY Sales, PY Sales, and % Difference in Sales.

### 4. Tornado Chart
- **Description**: Displays profit by subcategory using color coding—orange for losses and blue for profits—allowing quick assessment of profitability across segments.
- **Unique Feature**: Provides a clear visual representation of where losses are occurring relative to profits.

### 5. Step Line Charts
- **Description**: Illustrates sales and profit trends over time with average lines included for performance gauging.
- **Color Coding**: Blue indicates above-average performance while orange signifies below-average performance.

### 6. Histogram for Customer Distribution
- **Description**: Visualizes customer distribution based on the number of orders placed.
- **Advanced Feature**: Uses sequential color gradients from dark blue to light blue to represent frequency levels visually.

### 7. Top Customers by Profit Table
- **Description**: Lists top 10 customers based on profit with details such as rank, customer name, last ordered date, CY profit, CY sales, and number of orders.
- **Utility**: Enables businesses to identify high-value customers quickly for targeted engagement strategies.

### 8. Dynamic Filtering Options
- **Description**: Allows users to filter data dynamically by Year, Category, Subcategory, Region, State, or City.
- **Functionality Impact**: Changes in filters reflect immediately across all visualizations for cohesive analysis.

## Getting Started

### Prerequisites
- Tableau Desktop or Tableau Public installed on your computer.
- Access to the data source used for the dashboard (if applicable).

### How to Use the Dashboard
1. **Open the Dashboard**: Download the Tableau workbook file (`Sales_and_Customers_Dashboard.twb`) from this repository or access it directly via [this link](https://shorturl.at/0vDWS).
2. **Explore Metrics**: View key metrics displayed in the bans at the top of the dashboard.
3. **Interact with Visualizations**:
   - Hover over charts to see tooltips with detailed information.
   - Use sparkline charts to analyze monthly performance trends.
   - Check the bar in bar chart for a comparative view of CY vs. PY sales.
4. **Apply Filters**:
   - Use dynamic filters to narrow down data based on year, category, subcategory, region, state, or city; changes will reflect across all visualizations.
5. **Navigate Between Dashboards**:
   - Click navigation buttons to switch between Sales and Customers dashboards.
6. **Analyze Customer Data**:
   - Review customer distribution through the histogram and identify top customers by profit in the tabular format.

## Screenshots
![Sales Dashboard](https://github.com/user-attachments/assets/a17109f0-6fd3-475f-b184-6bad1592a6ad)
![Customers Dashboard](https://github.com/user-attachments/assets/69cd72e7-d491-4450-96d8-098b72f92df7)

## Contributing
Contributions are welcome! If you have suggestions for improvements or additional features, please feel free to submit a pull request or open an issue.

## Contact
For any inquiries or feedback, please contact [Swapnil Kakade] at [connectinglobe7@gmail.com].

---

Thank you for exploring the Sales and Customers Dashboard!
