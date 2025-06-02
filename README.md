# supplychainanalytics-
supply chain analytics project in python 

Supply Chain Shipment Pricing Data - Analysis and Modeling
This project performs exploratory data analysis and visualization on a real-world supply chain dataset, specifically focused on health commodity shipment and pricing data. It aims to derive insights into country-wise distribution, shipment modes, manufacturing sources, and pricing patterns.

📁 Dataset
File Name: SCMS_Delivery_History_Dataset.csv
Size: Approx. 570 KB
Records: 10,324

The dataset contains shipment records including country, pack price, shipment mode, manufacturing site, and other relevant features.

📊 Analysis Performed
Basic Data Inspection

Import necessary libraries and dataset

Display data types and sample records

Check for null values

Country-wise Shipment Distribution

Top 10 countries by shipment count (Bar Chart)

Country-wise Total Pack Price

Top 15 countries by total pack price (Bar Chart)

First Line Designation

Count of designations by type (Bar Chart)

Shipment Mode Analysis

Shipment mode distribution (Pie Chart)

Min, Max, and Mean for "Air" shipment mode

Manufacturing Site Insights

Unique manufacturing sites

Top 10 sites overall (Bar Chart)

Top 10 sites using "Air" shipment mode (Bar Chart)

Pack Price Distribution

Pack Price comparison across shipment modes (Bar Chart)

📈 Visualizations
Bar plots using Seaborn and Matplotlib

Interactive pie chart using Plotly

Visual emphasis on:

Shipment frequency

Price concentration

Mode of transportation

Manufacturing hotspots

🧾 Key Findings
Top Country (Total Pack Price): Nigeria - $25,620.72

Top Shipping Mode: Air

Air Shipment Stats:

Max: 1000 units

Min: 1 unit

Mean: 82.35 units

Top Manufacturing Site: Aurobindo Unit III, India (3,172 shipments)

Top Air Manufacturing Site: Aurobindo Unit III, India (1,694 air shipments)

🚀 How to Run
Clone this repository or open the notebook in Google Colab

Upload SCMS_Delivery_History_Dataset.csv

Run the Jupyter Notebook supply-chain-shipment-price-data-analysis.ipynb

🛠️ Libraries Used
pandas

numpy

matplotlib

seaborn

plotly

📌 Notes
All missing values are replaced with zero (fillna(0))

Analysis is purely descriptive; no predictive modeling is involved in this version

Suitable for anyone studying supply chain data or exploratory data analysis (EDA)

📄 License
This project is provided for educational and research purposes only. Dataset courtesy of a publicly available SCMS delivery data archive.








