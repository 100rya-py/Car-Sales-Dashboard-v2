# Car Sales & Inventory Dashboard

### 🚗 Project Overview
This project is a high-fidelity Power BI dashboard designed to monitor automotive sales performance, track growth metrics, and analyze customer demand across different regions.

The dashboard features a **minimalist, app-like interface** (designed with **Figma**) that allows users to navigate between different car models dynamically. It focuses on providing a clean user experience by hiding complex filters inside a collapsible "Slicer Panel," ensuring the main view remains clutter-free.

**Tools Used:** Power BI, Figma (for Background/UI), DAX (Data Analysis Expressions).

---

### 💼 Business Problems Solved
This dashboard is designed to help Sales Managers and Dealership Executives answer critical questions:

* **Sales Channel Efficiency:** By analyzing the split between **Direct Sales, Pre-Booking, and Third-Party** channels, stakeholders can identify which revenue stream is driving the most volume.
* **Revenue Segmentation:** The "Segmentation" analysis (Replacement vs. Servicing) helps distinguish between new product revenue and after-sales service revenue.
* **Budget vs. Actuals:** Tracking "Sale" against "Budget" KPIs allows for real-time performance monitoring and financial planning.
* **Logistics & Regional Performance:** The advanced Slicer Panel allows deep dives into **Shipping Modes** and **Regional** data to optimize supply chain decisions.

---

### 📊 Dashboard Tour

#### 1. Main Model Views (Dynamic Display)
The core of the dashboard features a dynamic layout where users can switch between different car models using navigation arrows.
* **Key Metrics (KPIs):** Displays clear headers for Total Sales (746K), Growth % (21.4%), Pre-Sales, and Budget targets.
* **Visuals:**
    * **Donut Chart:** Break down of sales by channel (Direct vs. Pre-Book vs. Third Party).
    * **Bar Chart (Segment):** Analyzes revenue sources like "Replacement" parts and "Servicing".
    * **Monthly Trend:** A trend chart showing performance from Jan to Dec to identify seasonal peaks.
* **Interaction:** Users can toggle between **Model 1 (SUV)**, **Model 2 (Sports)**, and **Model 3 (Classic)** to see specific data contexts or simply to browse the catalog visually.
* **Screenshot:**
    ![Model View](Insert_Model_Image_Link_Here)

#### 2. Collapsible Slicer Panel
To maintain a clean "Apple-style" aesthetic, I moved all filters into a hidden overlay panel.
* **Functionality:** A sidebar that slides out when the filter icon is clicked.
* **Filters Available:**
    * **Region:** Central, East, South, West.
    * **Ship Mode:** Analysis of logistics (First Class, Standard, etc.).
    * **Customer & State:** Granular search capability to find specific client data or state-level performance.
* **Screenshot:**
    ![Slicer Panel](Insert_Slicer_Panel_Image_Link_Here)

---

### 🧠 Technical Highlights
* **Navigation & Bookmarks:** Used Power BI **Bookmarks** and **Selection Panes** to create the "Car Switching" effect and the "Pop-up Slicer Panel," mimicking a web app experience.
* **Custom UI Design:** Designed the white, minimalist background and icons in **Figma** to move away from standard grid-based Power BI reports.
* **Dynamic Measures:** Implemented DAX to handle the switching logic between different views and time periods (2019-2022).

### 📂 Data Source
The dataset includes sales transactions, customer demographics, and shipping details.
* **Source:** [Insert Data Source Link Here]

---

### 📬 Contact
If you have any questions about the bookmark logic or the design process, feel free to reach out!
