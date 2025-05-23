# MongoDB–KNIME–DUNE Integration for Coin Analytics

This project presents a comprehensive, end-to-end data pipeline integrating **MongoDB**, **KNIME**, **DUNE Analytics**, and **Python** to analyze blockchain-based coins. The workflow showcases real-time data extraction, on-chain analytics, and interactive visualizations, demonstrating proficiency in data engineering, API integration, and blockchain analytics.

---

## 🔄 Project Workflow

### 1. **MongoDB Data Extraction via KNIME**

* Established a connection between **MongoDB** and **KNIME** to access structured data provided by the professor.
* Used KNIME's MongoDB Reader and query nodes to extract coin-related transaction data.

### 2. **On-Chain Analysis with DUNE**

* Constructed custom SQL-based queries and prompts within **DUNE Analytics** to evaluate metrics for a selected coin.
* Example Dashboard: [BONK Coin Analysis – DUNE](https://dune.com/michellelee/team2-memeproject2-bonk-analysis)

### 3. **DUNE API Integration with Python**

* Programmatically retrieved analytical results using the **DUNE API**.
* Parsed and processed returned datasets in Python for downstream integration.

### 4. **Storing Results in MongoDB**

* Leveraged **PyMongo** to insert DUNE-derived insights back into the **MongoDB** database for centralized storage and retrieval.

### 5. **Visualization in KNIME**

* Pulled enriched datasets from MongoDB into KNIME for further visualization and exploratory analysis.
* Designed interactive visual reports to present actionable blockchain insights.

---

## 🛠️ Tools & Technologies

* **MongoDB** – Primary data storage and management platform.
* **KNIME** – Workflow automation, ETL, and visual analytics.
* **DUNE Analytics** – Blockchain querying platform for smart contract and token data.
* **Python** – For API integration, data handling, and MongoDB automation.
* **DUNE API** – RESTful interface to fetch real-time blockchain insights programmatically.

---

## ✅ Key Highlights

* 🚀 Seamless integration of blockchain analytics into traditional BI workflows.
* 🔁 End-to-end automation from raw data extraction to insight delivery.
* 📈 Real-time coin performance dashboards and trend analysis powered by on-chain data.

