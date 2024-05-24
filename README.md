# Phonepe Transaction and User Data Visualization Web App

The Phonepe Transaction and User Data Visualization project is a Python-based solution that extracts data from the Phonepe Pulse Github repository, transforms and stores it in a MySQL database, and displays it through an interactive dashboard using Streamlit, Plotly and few other visualization and data manipulation libraries. The solution includes multiple pages with various visualizations, allowing users to select different facts and figures to display. The project is efficient, secure, and user-friendly, providing valuable insights and information about the data in the Phonepe Pulse Github repository.

## Prerequisites:
Before you begin, you will need to have a few tools and libraries installed on your machine:

Python 3.7 or higher. [Note: Streamlit only supports .py files as of now. So, notebook(.ipynb) files are not recommended]
Git software.
MySQL software.
The pandas, streamlit, plotly, seaborn, altair, and mysql-connector-python packages.
### Python
Python is the programming language used to develop this project. It is a popular high-level programming language known for its readability and versatility. It is widely used for web development, data analysis, and machine learning. It provides a powerful and flexible foundation for working with data.

### Git
Git is a version control system used for tracking changes in code. It is commonly used for collaborating on code and managing code changes. We used it here to clone the Pulse repository and extract the required data for analysis.

### Pandas
Pandas is a popular Python library used for data manipulation and analysis. We used pandas to clean and preprocess the data, create new features, and perform data analysis. It provides a wide range of functions and methods for working with data.

### MySQL
MySQL is an open-source relational database management system. We used it here to store and manage the cleaned and processed data. It provides a scalable and secure solution for managing large amounts of data.

### Streamlit
Streamlit is an open-source Python library used for building web applications. We used it here to create a multi-page application for visualizing the data. It provides an intuitive and user-friendly interface for exploring and analyzing data.

### Plotly
Plotly is a data visualization library used for creating interactive and dynamic plots. We used it here to create a variety of charts and visualizations, such as pie charts, bar charts, line plots, and choropleth maps. It provides a wide range of customization options and interactivity features.

## Features
### Home Page: This page provides an overview of the app and its features, along with links to other pages.
### Top Chart Page: This page displays various charts and graphs that give a summary of the transaction and user data using donut chart, bar plot and choropleth map.
### Transaction Page: This page displays the transaction data using various filters such as state, year & quarter in the form of transaction hotspots and breakdowns.
User Page: This page allows users to explore the user data using various filters such as state, year and quarter treemap, choropleth and density mapbox
Trend Page: This page shows the trend of transaction count and amount over time, and allows users to compare different time periods using line and bar plots
Comparison Page: This page allows users to compare different regions, transaction types using facet grids, grouped bar and pie chart.
