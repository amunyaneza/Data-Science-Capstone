Overview: The commercial space age has begun. Companies such as Virgin Galactic, Rocket Lab, Blue Origin, and SpaceX are making space travel and satellite launches more accessible.
Among them, SpaceX stands out by dramatically reducing launch costs through the reuse of Falcon 9’s first stage. While competitors may spend $165M+ per launch, SpaceX advertises launches at only $62M, largely because its first stages are often recovered and reused.

As a Data Scientist at SpaceY (a fictional competitor founded by billionaire Allon Musk), the task is to:

Analyze public SpaceX launch data


Predict whether Falcon 9’s first stage will successfully land


Estimate the cost of future launches


Build dashboards and visualizations to support business decisions

Instead of rocket science calculations, we'll rely on data wrangling, exploratory data analysis, visualization, and machine learning to provide insights.

Tech Stack:

Languages: Python, SQL

Libraries: Pandas, NumPy, Scikit-learn, Plotly, Dash, Folium, Matplotlib, Seaborn

Databases: MySQL / SQLite for SQL queries

Visualization: Plotly Dash, Folium, Jupyter Notebooks

Presentation: PDF (slides with methodology, results, and executive summary)

Project Goals:

Data Collection & Wrangling

Gather launch data from SpaceX’s API and web sources

Clean, transform, and prepare data for analysis

Exploratory Data Analysis (EDA)

SQL-based exploration

Interactive visualization (Plotly, Folium maps, Dash apps)

Identify patterns in launch success, payload mass, orbits, and landing sites

Predictive Modeling

Build ML models (Logistic Regression, SVM, Decision Trees, KNN)

Predict the likelihood of first-stage reusability

Estimate launch cost savings

Visualization & Dashboards

Interactive Plotly Dash dashboard for KPIs

Folium map of launch sites and outcomes

Graphical summaries of payloads, orbits, and success rates

How to Run:

Clone repo:

git clone https://github.com/yourusername/spacey-capstone.git
cd spacey-capstone

Install dependencies:

pip install -r requirements.txt


Run Jupyter notebooks for each module.

Launch dashboard:

python dashboards/dash_app.py


Open http://127.0.0.1:8050 in your browser

