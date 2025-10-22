
# ✈️ King Khalid International Airport Flights Dashboard (Power BI)

This project presents an interactive Power BI dashboard built to analyze and visualize flight operations data from **King Khalid International Airport (RUH)**.  
The dashboard provides insights into flight patterns, cancellations, airline performance, and route trends across time.

---

## 📊 Dashboard Overview

The dashboard is divided into **two main pages**:

### 🟠 **1. Flight Operations Overview**
- **Total Flights by Year:** 150,519 flights recorded in 2025.  
- **Unique Routes by Year:** 128 unique flight routes.  
- **On-Time Performance:** 99.92% of flights departed as scheduled.  
- **Top Destinations:** Jeddah, Dubai, Cairo, Abha, and Dammam.  
- **Top Airlines:** Saudi Arabian Airlines, flynas, flyadeal, and others.  
- **Flights Over Time:** Tracks flight frequency trends monthly and daily.

### 🟡 **2. Flight Status and Routes Analysis**
- **Weekly Flight Distribution:** Identifies peak flight days (Thursday & Sunday).  
- **Monthly Flight Trend:** Compares total monthly flights and averages.  
- **Canceled Flights Table:** Displays detailed cancellation records (Date, Airline, Route).  
- **Flight Paths Map:** Visualizes flight routes spanning multiple continents.

---

## 🧹 Data Preparation

Before visualization, the dataset was **cleaned and preprocessed**:
- Removed the value **“Unknown”** from the `Status` column.
- Handled missing values and duplicates.
- Standardized date and time formats.
- Ensured consistent airline and route naming conventions.

---

## 🧠 Insights & Key Findings

- **Saudi Arabian Airlines** dominates airport operations with the largest flight volume.
- **Thursday and Sunday** have the highest number of departures.
- **Summer months (June–August)** show peak flight activity.
- **Cancellations** are mostly concentrated on international routes to Europe and Asia.
- **On-time performance** remains exceptional throughout the observed period.

---

## 🧾 Dataset Information

**Source:** [Kaggle - King Khalid International Airport Flights Dataset](https://www.kaggle.com/datasets/mohammedalsubaie/king-khalid-international-airport-flights-dataset)

**Dataset Features:**
- Flight Date and Time  
- Airline  
- Origin and Destination  
- Route  
- Flight Status (Departed, Canceled, etc.)  
- IATA Codes  

**License:** Dataset provided publicly on Kaggle by [Mohammed Alsubaie](https://www.kaggle.com/mohammedalsubaie).

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Excel / Power Query**
- **Python (optional for preprocessing)**
- **Kaggle Dataset**

---

## 📈 Dashboard Screenshots

### Flight Overview Page
![Dashboard 1]([Screenshot%2025-10-22%104637.png](https://github.com/rahafalhuzali/King-Khalid-Airport_Traffic/blob/c2bf4df01c303248fff4be754a8832359cbbbd93/Screenshot%202025-10-22%20104637.png))

### Flight Status and Route Page
![Dashboard 2](https://github.com/yourusername/yourrepo/blob/main/Screenshot%202025-10-22%20105037.png)

---

## 🚀 How to Use
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mohammedalsubaie/king-khalid-international-airport-flights-dataset).  
2. Open the Power BI file (`KKIA_Flights.pbix`).  
3. Load the dataset and refresh the model.  
4. Explore visuals, apply filters, and analyze flight performance interactively.

---

## 💡 Future Improvements
- Add delay analysis by airline and route.
- Integrate weather data for cancellation correlation.
- Include forecast modeling for flight volume prediction.

---

## 👨‍💻 Author

**Developed by:** [Your Name]  
**Contact:** [Your Email or LinkedIn]  
**Date:** October 2025

---

⭐ If you like this project, please give it a **star** on GitHub!
