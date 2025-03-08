
![Logo](https://academy-public.coinmarketcap.com/optimized-uploads/de634d76314b44a5a2f79357c6b9f9a7.jpg)


# 🚀 Automating Crypto Website API Pull Project (Python)

This project automates the process of **retrieving cryptocurrency data** from the **CoinMarketCap API**, performing **data analysis & visualization using Python**. The data is **pulled** at regular intervals, **stored** in a CSV file, and **analyzed** to gain insights into cryptocurrency **price trends**.

## 📌 Key Features
- **Requests real-time cryptocurrency data** using the CoinMarketCap API.

- **Stores retrieved data in a CSV** file for further analysis.

- **Automates data collection** with a loop that runs every minute for 300 cycles.

- **Cleans and formats** the data using **pandas**.

- **Visualizes** cryptocurrency **price trends** using **seaborn and matplotlib**.
## 🛠️ Technologies Used
- **Python** – Core programming language
- **Requests** – For API communication
- **Pandas** – For data cleaning & transformation
- **Matplotlib & Seaborn** – For visualization
## 🚀 How It Works

1. **API Data Retrieval**
- **Sends a request** to the **CoinMarketCap API** to get cryptocurrency **listings**.
- **Extracts** relevant data and **normalizes** it into a structured format.

2. **Automated Data Pull**
- **Runs the data pull** function in a **loop** every minute for 300 iterations.
- **Saves data in a CSV** file, appending new entries.

3. **Data Cleaning and Transformation**
- **Converts timestamp columns** to readable datetime format.
- **Adjusts column names** for better readability.
- **Formats large numerical values** for better visualization.

4. **Data Visualization**
- Uses **seaborn** to create a **point plot** of **percent changes** over different timeframes.
- Generates a **line plot** to track Bitcoin price **fluctuations** over time.

## 🚀 How to Run the Project
1️⃣ **Clone this repository**:

    git clone https://github.com/Mohab-DataAnalyst/crypto-automation.git
    cd crypto-automation

2️⃣ **Install dependencies**:

    pip install requests pandas seaborn matplotlib

3️⃣ **Run the script**:

    python "Auto Crypto.py"

## 📎 Acknowledgements
- This project was inspired by [@Alex The Analyst.](https://youtu.be/KB2CtEDrglY?si=tUicFLHChz7cj1Vo)
- API: [@CoinMarketCap](https://coinmarketcap.com/api/)

## ✍️ Author
- 👤 [@Mohab-DataAnalyst](https://github.com/Mohab-DataAnalyst)
