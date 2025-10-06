# 📊 Overall Equipment Effectiveness (OEE) Dashboard in Excel

A simplified and automated Excel solution for tracking, analyzing, and improving Overall Equipment Effectiveness (OEE) in manufacturing environments.

---

## ✨ Project Overview

This repository provides a ready-to-use Excel template designed to help factories monitor their OEE. It's built for ease of use, combining straightforward data entry with a dynamic, insightful dashboard to drive continuous improvement.

**Key Features:**
-   **Automated OEE Calculation:** Instantly calculates OEE based on three core factors: Availability, Performance, and Quality.
-   **Intuitive Dashboard:** Visualizes key metrics (OEE, Availability, Performance, Quality) and trends at a glance.
-   **Machine-Specific Analysis:** Filter data to view OEE for individual machines or production lines.
-   **Data-Driven Insights:** Helps identify bottlenecks and prioritize improvement efforts.

---

## 🎯 What is OEE?

Overall Equipment Effectiveness (OEE) is a powerful metric that measures manufacturing productivity. It highlights how well your manufacturing assets are being utilized against their full potential.

The formula is a combination of three key factors:

**`OEE = Availability × Performance × Quality`**

-   **Availability:** The percentage of scheduled production time that the machine is actually running. (Planned Production Time - Unplanned Downtime) / Planned Production Time
-   **Performance:** The speed at which the machine runs compared to its ideal speed. (Total Parts Produced / Ideal Cycle Time) / (Planned Production Time - Unplanned Downtime)
-   **Quality:** The percentage of good parts produced out of the total parts produced. (Total Parts Produced - Defective Parts) / Total Parts Produced

---

## 🏗️ How It Works (Structure)

The Excel file is divided into two main sheets:

### 1. 📋 Data Entry Sheet

This is where all raw production data is logged daily. It's designed to be straightforward, requiring minimal input to generate comprehensive insights.

**Key Data Points:**
-   **Date:** The day of production.
-   **Machine ID:** Identifier for the specific machine or production line.
-   **Planned Production Time (min):** Total minutes the machine was scheduled to run.
-   **Unplanned Downtime (min):** Minutes the machine was unexpectedly stopped (e.g., breakdowns, material shortages).
-   **Ideal Cycle Time (sec/part):** The theoretical fastest time to produce one part.
-   **Total Parts Produced:** Total count of all parts (good and defective) made during the shift.
-   **Defective Parts:** Number of parts that did not meet quality standards.
-   **Ideal Parts/min:** The target production rate (calculated for convenience).

*(Example image of the Data Entry Sheet)*
![Data Entry Sheet](link-to-your-data-entry-sheet-image.png)

### 2. 📊 Dashboard Overview

This sheet automatically pulls data from the 'Data Entry' sheet and presents it through a clean, interactive dashboard.

**Dashboard Components:**
-   **Overall OEE Score:** The primary metric, prominently displayed.
-   **Availability, Performance, Quality Scores:** Breakdown of the three OEE factors.
-   **OEE Trend Chart:** Visualizes OEE performance over time to identify patterns.
-   **Machine Filters:** Allows users to select and analyze OEE for specific machines.

*(Example image of the OEE Dashboard)*
![OEE Dashboard](link-to-your-dashboard-image.png)

---

## 🚀 Key Benefits for Your Factory

This OEE dashboard isn't just for reporting numbers; it's a powerful tool for driving action and continuous improvement.

-   **Pinpoint Losses:** Quickly identify if breakdowns (Availability), slow cycles (Performance), or defects (Quality) are your biggest bottlenecks.
-   **Data-Driven Decisions:** Move beyond guesswork. Use concrete data to focus improvement efforts where they will have the greatest impact.
-   **Track Progress:** The trend chart provides instant feedback on whether your operational changes are yielding desired results.
-   **Boost Profitability:** Directly reduce waste, optimize output, and lower production costs by improving equipment effectiveness.

---

## 💡 Getting Started

1.  **Download:** Clone this repository or download the Excel file directly.
2.  **Input Data:** Go to the 'Data Entry' sheet and start populating it with your production data.
3.  **Monitor Dashboard:** Switch to the 'Dashboard' sheet to see your OEE metrics update in real-time.
4.  **Customize (Optional):** Adjust conditional formatting, add more machine IDs, or extend the data range as needed.

---

## 🤝 Contribution

Feel free to fork this repository, suggest improvements, or submit pull requests. Any feedback or enhancements are welcome!

