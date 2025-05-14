# 📊 Call Center Analysis – October 2020

This project features a fully functional and visually engaging **dashboard created in Microsoft Excel** that analyzes customer call center activity for October 2020. The dataset captures call records across several U.S. cities and provides insights into **customer sentiment**, **call reasons**, **response times**, and **preferred communication channels**. The primary goal was to turn raw CSV data into a professional dashboard that could help management teams understand performance and identify improvement opportunities.

---

## 📂 Project Files

| File Name             | Description                                          |
|-----------------------|------------------------------------------------------|
| `Call Center.csv`   |  Raw dataset                 |
| `Cleaned Call Center file'  | Cleaned dataset used for building the dashbord         |
| `Call Center Dashboard'  | Final dashboard exported from Excel          |
| `README.md`           | Call Center Analysis (this file)                    |

---

## 🧾 Dataset Description

The dataset consists of call center data collected during October 2020, covering:

- `Call_Day` – The day of the month when the call occurred
- `call_center` – Location of the call center (City, State)
- `sentiment` – Sentiment classification of the call (Very Positive to Very Negative)
- `reason_for_call` – Why the customer contacted support (Billing, Payments, Service Outage)
- `response_time_category` – Categorization of response time (Above SLA, Within SLA, Below SLA)
- `channel` – The method of communication (Chatbox, Email, Web)

---

## 🛠️ Tools Used

| Tool           | Purpose                                 |
|----------------|-----------------------------------------|
| **Excel**      | Data cleaning, analysis, chart creation |
| **Pivot Tables** | Summarizing and aggregating data       |
| **Charts**     | Bar, Column, Pie, and Map visualizations|
| **PDF Export** | Finalizing and sharing dashboard output |

---

## 📐 Methodology – Step-by-Step

### Step 1: Data Import and Cleaning
- Loaded the `.csv` file into Microsoft Excel.
- Standardized values across categories to prevent inconsistencies (e.g., consistent naming of states and call reasons).
- Removed duplicates and ensured numeric fields were properly formatted.
- Created helper columns where necessary for categorization and aggregation.

### Step 2: Data Transformation
- Used **Pivot Tables** to calculate:
  - Total number of calls per center, sentiment, reason, channel
  - Calls categorized by SLA compliance
  - Regional breakdown by U.S. states

### Step 3: Visual Design (Dashboard Layout)
- Created a one-page dashboard layout in Excel using:
  - **Bar charts** for calls by by response time, call by sentiment, and sentiment by call center
  - **Stacked column charts** for reason for call, call by call center and total inbound calls
  - **Donut chart** for Call by channel distribution including call-center,	chatbot, email, and	web
  - **Map visualization** (using filled-maps) to show calls by state
  - **Slicers** for call day and call center
- Used cell formatting, cell referencings, and labeled sections for easy navigation.

---

## 📊 Dashboard Sections – Deep Dive

### 1. Total Inbound Calls
- **Total Calls**: `32,941`
- This KPI is prominently displayed to give stakeholders a quick glance at the customer service demand for October 2020.

---

### 2. Calls by Call Center

| Call Center     | Total Calls |
|-----------------|-------------|
| Los Angeles, CA | 13,734      |
| Chicago, IL     | 8,754       |
| Baltimore, MD   | 6,026       |
| Denver, CO      | 3,928       |

🧠 **Insight**:
- Los Angeles clearly had the highest number of calls, possibly due to a larger customer base or more service-related issues.

---

### 3. Calls by Sentiment

Sentiment categories included:
- Very Positive
- Positive
- Neutral
- Negative
- Very Negative

🧠 **Insight**:
- The majority of the calls were classified as **positive or very positive**, indicating good customer service across most centers.
- However, there were still a notable number of **negative** and **very negative** interactions, particularly in high-traffic centers. This warrants investigation into agent training or operational bottlenecks.

---

### 4. Calls by Reason

| Reason           | Call Volume |
|------------------|-------------|
| Service Outage   | 20,625      |
| Payments         | 8,148       |
| Billing Question | 4,168       |

🧠 **Insight**:
- Service outages made up **more than 60%** of the total calls, showing a clear issue in service delivery or infrastructure.
- Prioritizing investments in technical reliability and monitoring could drastically reduce call volume and improve satisfaction.

---

### 5. Calls by SLA Response Time

Response time categories:
- Above SLA – took too long
- Within SLA – met target time
- Below SLA – resolved faster than expected or missed key steps

🧠 **Insight**:
- A significant portion of calls were resolved **within SLA**, reflecting efficient handling.
- The **"Above SLA"** category highlights delays that could affect customer satisfaction.
- "Below SLA" calls should also be reviewed to ensure quality wasn't sacrificed for speed.

---

### 6. Geographic Distribution (Calls by State)
- Visualized using a U.S. map powered by Bing.
- Shows which states contributed the most to the call volume.

🧠 **Insight**:
- Useful for regional management and to forecast staffing needs or marketing focus in high-demand areas.

---

### 7. Communication Channels Used

| Channel  | Volume | Share  |
|----------|--------|--------|
| Chatbox  | 8,256  | 25%    |
| Email    | 7,470  | 23%    |
| Web      | 6,576  | 20%    |

🧠 **Insight**:
- Chatbox is the most popular contact method, likely due to its speed and accessibility.
- Email and web are also important and indicate a diverse support ecosystem.
- Understanding channel usage helps allocate staff and automate support options effectively.

### Dashboard Snapshot: Call Center Dashboard
- Final dashboard snapshop for presentation purposes and easy sharing with stakeholders.
![image](https://github.com/user-attachments/assets/56048541-b8e1-43d1-a989-2a43cd1dab83)

---

## 🔍 Final Insights

1. **High Call Volume** in Los Angeles demands additional support or root cause analysis.
2. **Service Outages** are the most frequent complaint—technical improvement needed.
3. Most customers report **positive experiences**, but negative cases should be addressed.
4. **SLA monitoring** is essential to maintain service standards.
5. Customers prefer **chat-based support**, suggesting automation and chatbot investment would yield ROI.

---

## ✨ Skills Demonstrated

- 🔹 Excel data cleaning and wrangling
- 🔹 Pivot table mastery for summaries
- 🔹 Chart and graph development for storytelling
- 🔹 Dashboard layout and formatting
- 🔹 Business analysis and insight extraction
- 🔹 PDF report preparation

---
