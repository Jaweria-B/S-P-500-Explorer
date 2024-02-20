# S&P 500 Stocks Explorer 

This web application retrieves data about companies listed on the S&P 500 index and provides users with interactive tools to explore and analyze the data. Users can visualize the stock closing prices of selected companies, download company data as a CSV file, and filter companies by sector.

## Features

- **Data Retrieval**: Data about S&P 500 companies is fetched from Wikipedia using web scraping techniques.
  
- **Sector Selection**: Users can select specific sectors of interest to filter the displayed companies.
  
- **Interactive Display**: The application dynamically updates the displayed data based on user selections, allowing for an interactive and customizable experience.
  
- **CSV Download**: Users can download the displayed company data as a CSV file for further analysis.
  
- **Stock Price Visualization**: The application fetches year-to-date stock price data for selected companies using the yfinance library and plots their closing prices on interactive charts.
  
- **Responsive Design**: The layout of the application is responsive, providing a seamless experience across different devices and screen sizes.

## Usage

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/Jaweria-B/S-P-500-Explorer.git
   ```

2. Navigate to the project directory:

   ```
   cd S-P-500-Explorer
   ```

3. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Run the Streamlit application:

   ```
   streamlit run app.py
   ```

5. Access the application in your web browser at `http://localhost:8501`.

## Input Method

Users can interact with the application through the following methods:

- **Sector Selection**: Users can select sectors of interest from the sidebar to filter the displayed companies.

- **Number of Companies Slider**: Users can adjust the slider to choose the number of companies they want to visualize on the stock closing price charts.

- **Show Plots Button**: Clicking the "Show Plots" button triggers the visualization of stock closing prices for the selected companies.

- **CSV Download**: Users can download the displayed company data as a CSV file by clicking the "Download CSV File" link.

## Dependencies

- Streamlit: For building the interactive web application.
  
- Pandas: For data manipulation and analysis.
  
- Matplotlib: For plotting the stock closing price charts.
  
- yfinance: For fetching stock price data.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please open an issue or submit a pull request.

