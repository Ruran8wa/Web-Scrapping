# Smartphone Pricing Data Scraping and Visualization.

## Overview.

This project focuses on scraping smartphone pricing data from various online retailers using Selenium WebDriver and then visualizing the pricing trends using Chart.js and jQuery.

## System Description.

The system consists of a Node.js application that utilizes Selenium WebDriver for web scraping. It also employs Express, EJS, Chart.js, and jQuery for creating interactive visualizations. The primary objective is to offer insights into smartphone pricing trends over time across different retailers.

## Prerequisites.

- Node.js installed
- npm packages (express, ejs, selenium-webdriver)

## Setup.

1. **Clone the repository**

   ```bash 
   git clone https://github.com/Ruran8wa/Web-Scrapping.git
   cd web_scraping
   ```

2. **Install dependencies**

	```bash
	npm install
	```

3. **Run the scraping script and start the server**

	```bash
	node script.js
	```

4. **Open in Browser**

	Open your web browser and navigate to the following link to view the visualization.

	```bash
	http://localhost:5500/
	```

## Project Structure.

- **script.js**: Contains the web scraping script using Selenium and the Express server setup.
- **public/scraped_data.json**: JSON file containing the scraped smartphone pricing data.
- **views/index.ejs**: HTML template for rendering the visualization using Chart.js and jQuery.

## Visualization.

The visualization displays a line chart showcasing the pricing trends of smartphones over time. The chart includes interactive features such as zooming, panning, and tooltips displaying detailed information.

## Acknowledgments.

- The project utilizes Chart.js for creating interactive charts.
- Selenium WebDriver is employed for web scraping smartphone pricing data.
- Express and EJS are used to set up the server and render the HTML template.
