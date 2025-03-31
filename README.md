# 🚖 Uber Trip Analysis – Power BI Dashboard  

![Uber Screenshot](https://github.com/jay-parab/Uber_Trip_Analysis/blob/main/Uber%20Trip%20Analysis%20Dashboard%20Screenshot.png?raw=true)

## 📌 Project Overview  
This Power BI dashboard analyzes Uber trip data to uncover **booking trends, revenue insights, and trip efficiency metrics**. It helps stakeholders **optimize pricing, enhance operational efficiency, and improve customer experience** by leveraging interactive visualizations and data analytics.  

## 📂 Dataset Overview  
The dataset consists of two key tables:  

1️⃣ **Trip Details Table** – Contains information on individual Uber rides, including timing, distance, fare details, and vehicle type.  
2️⃣ **Location Table** – Maps numerical **Location IDs** to actual area names and cities, enabling **pickup and drop-off analysis**.  

---

### 📄 **Trip Details Table**  
| Column Name        | Description  |
|--------------------|-------------|
| **Trip ID**       | Unique identifier assigned to each Uber trip. Helps track individual rides.  |
| **Pickup Time**   | Date and time when the passenger was picked up. Used for analyzing trip trends, peak hours, and total ride duration.  |
| **Drop-Off Time** | Date and time when the passenger was dropped off. Used to calculate trip duration and analyze trip completion trends.  |
| **Passenger Count** | Number of passengers in the trip. Helps understand ride-sharing patterns and demand for different vehicle types.  |
| **Trip Distance** | Distance covered during the trip (in miles). Used for fare calculation, efficiency analysis, and identifying long/short trips.  |
| **PULocationID** | Numeric code representing the pickup location. Linked to a location table to get the actual pickup area name.  |
| **DOLocationID** | Numeric code representing the drop-off location. Used for destination analysis, ride patterns, and demand forecasting.  |
| **Payment Type** | Mode of payment (e.g., credit card, cash, wallet). Helps in financial analysis and understanding customer preferences.  |
| **Fare Amount** | Base fare charged for the trip before additional fees. Essential for revenue analysis and pricing strategy.  |
| **Surge Fee** | Extra charge applied during high-demand periods. Helps in understanding surge pricing patterns and peak-hour demand.  |
| **Vehicle Type** | Type of Uber service used (e.g., UberX, UberXL, Uber Black). Used for analyzing vehicle demand and customer preferences.  |

---

### 📄 **Location Table**  
| Column Name  | Description  |
|-------------|-------------|
| **LocationID** | Unique identifier for each location in the dataset. Serves as a key to link locations to trips.  |
| **Location** | Name of the area or neighborhood where pickups and drop-offs occur.  |
| **City** | City in which the location exists, helping in geographic segmentation and analysis.  |

---
## 📊 Key KPIs & Insights  

### ✅ Dashboard 1: Overview Analysis  
✔ **Total Bookings** – Number of trips over a selected period  
✔ **Total Booking Value** – Total revenue from all trips  
✔ **Average Booking Value** – Revenue per trip  
✔ **Total & Average Trip Distance** – Travel patterns and efficiency  
✔ **Average Trip Time** – Duration analysis  

#### 🔹 Key Features  
🔸 **Measure Selector** – Users can switch between key KPIs dynamically  
🔸 **Filtering by Payment Type & Trip Type** – Analyze revenue by cash, card, or wallet payments  
🔸 **Top 5 Locations by Bookings** – Identify high-demand areas  
🔸 **Most Preferred Vehicle per Location** – Optimize vehicle distribution  
🔸 **Conditional Formatting & Sorting** – Highlighting key trends  

📸 **Dashboard Screenshot:**  
![your-dashboard-1-screenshot-url-here](https://github.com/jay-parab/Uber_Trip_Analysis/blob/main/Uber%20Trip%20Analysis%20Dashboard%20Screenshot.png?raw=true)

---

### ✅ Dashboard 2: Time Analysis  
✔ **Total Bookings by Time** – Peak demand hours and off-peak trends  
✔ **Bookings by Day Name** – Weekday vs. weekend patterns  
✔ **Heatmap Analysis (Hour vs. Day of the Week)** – Identifies high-demand time slots  

#### 🔹 Key Features  
🔸 **Global Dynamic Measure Selector** – Updates all charts dynamically  
🔸 **10-Minute Interval Trends** – Detects micro-trends in ride demand  
🔸 **Heatmap (Hour vs. Day)** – Pinpoints surge pricing opportunities  

📸 **Dashboard Screenshot:**  
![Dashboard 2 - Time Analysis](https://github.com/jay-parab/Uber_Trip_Analysis/blob/main/Uber%20Trip%20Analysis%20Dashboard%202%20Screenshot.png?raw=true)

---

### ✅ Dashboard 3: Details Tab  
✔ **Grid Table for Detailed Records** – View granular trip details  
✔ **Drill-Through Functionality** – Right-click on visuals to explore specific data points  
✔ **Data View Bookmark** – Toggle between filtered and full dataset  

#### 🔹 Additional Enhancements  
🔹 **Dynamic Titles** – Charts update based on user selections  
🔹 **Clear Slicer Button** – One-click reset for all filters  
🔹 **Download Raw Data Button** – Export data for further analysis  
🔹 **Conditional Formatting & Tooltips** – Improved user experience  

📸 **Dashboard Screenshot:**  
![Dashboard 3 - Details Tab](https://github.com/jay-parab/Uber_Trip_Analysis/blob/main/Uber%20Trip%20Analysis%20Dashboard%203%20Screenshot.png?raw=true)

---

## 🎥 Live Demo & Screenshots  
📹 **[Video Walkthrough](https://drive.google.com/file/d/1dg06iLdMwgeDxESQ33ix5Hs3BiSuPAFt/view?usp=sharing)** – See the dashboard in action  

---

## 🛠 Power BI Implementation Techniques  
🟢 **DAX Measures:** Created dynamic calculations for KPIs  
🟢 **Power Query Transformations:** Cleaned and preprocessed the data  
🟢 **Disconnected Tables & Measure Selector:** Enabled dynamic visual updates  
🟢 **Drill-Through & Bookmarks:** Enhanced data exploration  
🟢 **Heatmaps & Conditional Formatting:** Visualized trends effectively  

---

## 💡 Key Learnings & Challenges  
✔ **Optimizing Performance** – Efficiently managing large datasets in Power BI  
✔ **Dynamic Visuals & Interactivity** – Creating an engaging user experience  
✔ **Enhancing Analytical Depth** – Extracting valuable insights for decision-making  

---

