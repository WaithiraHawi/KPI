### Call Center KPI Analysis

This project is a detailed exploratory and performance analysis of a call center's operations using a real-world dataset provided in `CallCenter.xlsx`. The goal is to calculate, visualize, and interpret key performance indicators (KPIs) to assess agent productivity, customer experience, and operational efficiency.

<img width="1024" height="1536" alt="KPIs" src="https://github.com/user-attachments/assets/4511aa82-a4b9-4421-8bc6-57b477dc9383" />

## KPIs Analyzed

The notebook calculates the following KPIs:

### **Core KPIs**

| KPI                       | Description                                 |
| ------------------------- | ------------------------------------------- |
| **Call Answer Rate**      | % of incoming calls answered by agents      |
| **Call Abandonment Rate** | % of calls dropped before being answered    |
| **Average Talk Time**     | Avg. time agents spend talking to customers |
| **Average Hold Time**     | Avg. time customers are put on hold         |
| **Longest Wait Time**     | Longest wait recorded on a given day        |

### **Advanced KPIs**

| KPI                             | Description                                                       |
| ------------------------------- | ----------------------------------------------------------------- |
| **Average Handling Time (AHT)** | Talk Time + Hold Time                                             |
| **Calls Per Agent**             | Total calls handled ÷ number of agents                            |
| **Agent Utilization Rate**      | Total talk time ÷ total agent available time (based on 8 hrs/day) |


## Visualizations

Performance visualization created using `matplotlib` include:

* **Call Answer Rate Over Time**
* **Call Abandonment Rate with Dynamic Y-Axis**
* **Talk Time vs Hold Time**
* **Longest Wait Time Trends**
* **Handling Time and Utilization Insights**

## Tools Used

| Tool               | Purpose                            |
| ------------------ | ---------------------------------- |
| `Pandas`           | Data cleaning and KPI calculations |
| `Matplotlib`       | Data visualization                 |
| `Jupyter Notebook` | Interactive analysis               |
| `Excel`            | Original data source               |


## Findings

* Most days had a Call Answer Rate > 99%, indicating high service availability.
* Call Abandonment Rates were generally low, but there were spikes on certain days.
* Longest Wait Times fluctuated, implying inconsistency in peak day handling.
* Some dates had missing talk/hold time data, which limited the accuracy of this analysis.
* The calls per Agent daily was an average of between 160–200, possible suggesting a high work-agent load.


## Recommendations
* Track Customer Satisfaction Scores (CSAT) for QA insights.
* Investigate days with longest wait time to improve staffing strategies.
* Adding an (ACW) for accurate AHT measurement.
