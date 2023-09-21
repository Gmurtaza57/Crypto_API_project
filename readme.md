**CoinMarketCap API Data Retrieval & Analysis**
A Python-based project for fetching, normalizing, and analyzing cryptocurrency data from CoinMarketCap's API.

*Features*
Automated hourly data retrieval from CoinMarketCap's API.
Normalization of JSON data into a pandas DataFrame.
Visualization of cryptocurrency price trends using Seaborn.
Efficient data storage and aggregation mechanisms.
Special emphasis on analyzing Bitcoin price trends.
*Prerequisites*
To use this repository, you should have the following packages installed:

requests
pandas
json
os
time
seaborn
matplotlib
Getting Started
Clone the repository:
bash
Copy code
git clone [repository_url]
Navigate to the cloned directory and install the required Python packages.

Run the main script:

bash
Copy code
python [script_name].py
Usage
Set your CoinMarketCap's API Key in the headers dictionary.
Run the api_runner function to fetch, normalize, and append data.
Use the various data transformation blocks to prepare your dataset for analysis.
Visualize trends using Seaborn.
Note
Ensure you have set the iopub data rate limit if running in a Jupyter notebook environment using:

css
Copy code
jupyter notebook --NotebookApp.iopub_data_rate_limit=1e10
Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
