# 📊 Viewership Analysis Project

## 📌 Summary of the Case Study
This case study demonstrates how Python and SQL-compatible tools can be used to **analyze video viewership data** stored in an Excel file. The project focused on importing, cleaning, and exploring the dataset to prepare it for further analysis. The goal was to transform raw logs into **insights about customer behavior, platform usage, and content trends**.

---

## 🔍 How the Case Study Was Done
1. **Data Import**
   - Imported essential Python libraries:  
     - `pandas` → For data manipulation and analysis.  
     - `numpy` → For numerical operations.  
   - Installed `openpyxl` to enable reading `.xlsx` files.

2. **Data Loading**
   - Defined the file path:  
     `/Workspace/Users/khozabonginkosi6@gmail.com/Viewership Analysis .xlsx`
   - Loaded the dataset into a Pandas DataFrame using `pd.read_excel()`.
   - Displayed the dataset for preview and exploration.

3. **Dataset Exploration**
   - Columns included:  
     - `DateID` → Date of the event (YYYYMMDD format).  
     - `CustomerID` → Unique identifier for the customer.  
     - `TotalTimeWatched` → Total viewing time in seconds.  
     - `Platform` → Platform used (e.g., Leanback, Mobile).  
     - `PlayEventType` → Type of event (e.g., LiveTV, VOD).  
     - `VideoTitle` → Title of the video watched.  
   - Sample records were reviewed to understand structure and data quality.

4. **Planned Next Steps**
   - Perform **exploratory data analysis (EDA)**.  
   - Aggregate viewership by **platform, event type, or video title**.  
   - Build **dashboards for executive reporting**.  
   - Identify **trends and insights in customer behavior**.

---

## 📊 Insights Found
- The dataset provides a **granular view of customer activity**, including platforms used and event types.  
- **Viewing time analysis** highlights engagement levels across different customers and content.  
- **Platform usage trends** (e.g., Leanback vs. Mobile) can reveal customer preferences.  
- **Event type breakdown** (LiveTV vs. VOD) helps identify which formats drive higher engagement.  
- Video title exploration offers insights into **popular content and consumption patterns**.  

---

## 🎯 Summary of Findings
By loading and exploring the dataset, the project uncovered:  
- A clear structure for analyzing **viewership behavior**.  
- Opportunities to segment customers by **platform, event type, and content preferences**.  
- A foundation for building **dashboards and reports** that support executive decision-making.  

This demonstrates how Python and Pandas can transform raw Excel logs into **business intelligence** for **content strategy, platform optimization, and customer engagement analysis**.

---

## 🛠️ Tools Used
- **Python** → Programming environment.  
- **pandas** → Data manipulation and analysis.  
- **numpy** → Numerical operations.  
- **openpyxl** → Excel file support for `.xlsx` format.  
- **Excel** → Original data source.  
- **Optional BI Tools** → Power BI, Looker Studio for dashboard visualization.  

