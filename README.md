# Adidas-Interactive-Sales-Dashboard


# **Adidas Interactive Sales Dashboard**

This project presents an interactive **Sales Dashboard** for Adidas, built with **Streamlit**, **Plotly**, and **Pandas**. The dashboard provides users with detailed insights into Adidas' total sales, sales by retailer, sales over time, sales by state, and region-wise sales in a treemap format. The dashboard is designed to visualize key metrics and empower stakeholders with actionable business intelligence.

### **Features**
- **Retailer-wise Sales Visualization**: Bar chart showing total sales by different retailers.
- **Sales Over Time**: A line chart displaying the trend of total sales over time (monthly).
- **State-wise Sales & Units Sold**: A bar and line chart comparing total sales and units sold across different states.
- **Regional & City-wise Sales**: A treemap displaying the distribution of total sales by region and city.
- **Downloadable Data**: Options to download sales data in CSV format for further analysis.
  
### **Technologies Used**
- **Streamlit**: An open-source app framework to create custom data dashboards in Python.
- **Plotly**: A data visualization library for creating interactive charts.
- **Pandas**: A data manipulation library to handle large datasets and perform operations.
- **Pillow (PIL)**: A Python Imaging Library to handle image operations like displaying the Adidas logo.
- **Datetime**: To fetch the current timestamp and display the last updated time.

### **Project Setup and Installation**
To run the Adidas Interactive Sales Dashboard locally, you will need to install the necessary libraries. You can follow these steps to set up the environment:

#### **1. Install the dependencies**
Create a new virtual environment (optional) and install the required libraries using `pip`:

```bash
pip install streamlit pandas plotly pillow
```

#### **2. Prepare the Excel Data File**
Make sure the Excel file (`Adidas.xlsx`) containing the sales data is available in the project directory. The file should include columns like:
- `Retailer`
- `TotalSales`
- `UnitsSold`
- `InvoiceDate`
- `State`
- `City`
- `Region`

You will also need to have the Adidas logo image (`adidas-logo.jpg`) in the same directory for the app to display the logo.

#### **3. Run the Streamlit App**
Once everything is set up, run the Streamlit app with the following command:

```bash
streamlit run app.py
```

### **App Overview**
#### **1. Title and Last Updated Information**
The app displays the title "Adidas Interactive Sales Dashboard" at the top, and the last updated timestamp is shown alongside.

#### **2. Total Sales by Retailer**
A bar chart visualizes the total sales by different retailers. You can hover over each bar to get more details.

#### **3. Sales Data Table and Download**
An expandable section displays retailer-wise sales data, and users can download this data as a CSV file.

#### **4. Total Sales Over Time**
A line chart shows how total sales have changed over time, grouped by month.

#### **5. Sales Data by State**
A combination of a bar chart (for total sales) and a line chart (for units sold) displays state-wise data. Users can also download this data as CSV.

#### **6. Regional and City Sales Treemap**
A treemap visualizes the total sales by region and city. This chart provides a geographical perspective of sales performance.

#### **7. Raw Data and Download**
The raw sales data is available for users to download as a CSV file. This allows users to perform their own analysis.

### **App Layout**
The app has a clean layout with multiple columns to display:
- **Sales metrics and visualizations**: All charts are dynamically updated based on the data.
- **Expanding sections**: Users can expand sections to view data or download files.
- **Responsive design**: The app uses `Streamlit`'s column layout and responsive settings for a user-friendly experience.

### **Visualizations**
1. **Bar chart for Retailer-wise Sales**: Displays the total sales for each retailer.
2. **Line chart for Total Sales Over Time**: Shows the monthly trend of total sales.
3. **Bar & Line chart for Sales and Units Sold by State**: A combination chart comparing total sales and units sold across states.
4. **Treemap for Regional and City-wise Sales**: A hierarchical chart that displays the distribution of total sales by region and city.

### **Data Files**
- **Adidas.xlsx**: The main Excel file containing the sales data for Adidas.
- **adidas-logo.jpg**: The logo image for the app.

### **Downloadable CSVs**
- **RetailerSales.csv**: A CSV file containing retailer-wise sales data.
- **MonthlySales.csv**: A CSV file containing total sales by month.
- **Sales_by_UnitsSold.csv**: A CSV file containing total sales and units sold by state.
- **Sales_by_Region.csv**: A CSV file containing total sales by region and city.
- **SalesRawData.csv**: A CSV file with the raw sales data.

### **Contributions**
Feel free to fork the repository, make changes, and create pull requests. Contributions to improve the app or add more visualizations are always welcome.

### **License**
This project is open-source and available under the MIT License.

---

Let me know if you need any more modifications or explanations for the README! 😊
