# 👥📦 Advanced Product Customer Grouping Analysis Project  

---

## 📑 Table of Contents  

- <a href="#project-overview">📖 Project Overview</a>  
- <a href="#project-objectives">🎯 Project Objectives</a>  
- <a href="#approach-execution">⚙ Approach & Execution</a>  
- <a href="#key-skills">🧠 Key Skills Demonstrated</a>  
- <a href="#tools-used">🛠 Tools Used</a>  
- <a href="#project-outcome">📊 Project Outcome</a>  
- <a href="#repo-contents">📂 Repository Contents</a>  
- <a href="#project-use">🚀 How to Use This Project</a>  
- <a href="#future-enhancements">🌟 Future Enhancements</a>  
- <a href="#contact">📬 Connect with Me</a>  
- <a href="#project-visual">📷 Project Snapshot</a>  

---

## <span id="project-overview">📖 Project Overview</span>  

This project was designed to demonstrate **real-world customer-product analysis** using **Microsoft Power Query**.  

The dataset included several important fields such as: 

- 📦 **Product Name**  
- 👤 **Customer Name**  
- 🔢 **Quantity**  
- 💵 **Price**  
- 📅 **Purchase Date**  
- 🏙️ **City**  
- 💳 **Payment Mode**  

The key challenge in this project was handling **repeated customer names** in the dataset and summarizing their purchase behavior efficiently.  

The **main goal** was to transform the dataset in such a way that:  

1. Each **unique product** appeared only once.  
2. A new column displayed **how many times** that product was purchased.  
3. Another column listed **all customers** who bought that product — combined neatly in a **comma-separated format**.  

This project demonstrates a practical example of **advanced grouping and aggregation** using Power Query, often used in business analytics for **customer segmentation and product performance insights**.  

---

## <span id="project-objectives">🎯 Project Objectives</span>  

- Create a **unique list of products** from a transactional dataset.  
- Calculate **purchase frequency** for each product.  
- Combine **all customer names** linked to each product into a single cell.  
- Use **Advanced Group By** in Power Query to automate this transformation.  
- Build a **clean, readable, and analysis-ready output** for Excel reporting.  

---

## <span id="approach-execution">⚙ Approach & Execution</span>  

### **1. Dataset Preparation**  

- The sample dataset was first generated using **ChatGPT**, in CSV format.  
- Each record included *Product Name*, *Customer Name*, *Quantity*, *Price*, *Purchase Date*, *City*, and *Payment Mode*.  
- The dataset contained **repeated customer names**, simulating real-world purchasing data.  

### **2. Importing Data into Power Query**  

- Imported the CSV file into Excel.  
- From the **Data Tab**, navigated to **Get Data → From Text/CSV** to open the file in **Power Query Editor**.  

### **3. Grouping & Aggregation**  

- Selected the **Group By** option in Power Query.  
- Switched to **Advanced Group By** to perform multiple aggregations simultaneously.  

### **4. Creating Aggregations**  

- Grouped data by **Product Name**.  
- Added a new aggregation column **Product Count** using the **Count Rows** operation to calculate how many times each product was purchased.  
- Added another aggregation column **List of Customers**, using **All Rows** to store a mini table of customers for each product.  

### **5. Creating a Custom Column**  

To transform the customer table into a **comma-separated text list**, created a new custom column using the following formula:  

= Text.Combine([List of Customers][Customer Name], ", ")

This formula combines all customer names who purchased a specific product into a single cell, separated by commas.  

---

### **6. Loading Cleaned Data**  

After transformation, used **Close & Load To → Excel Sheet** to export the summarized table back to Excel.  

The final dataset was structured and ready for further **data visualization** or **business reporting**.  

---

## <span id="key-skills">🧠 Key Skills Demonstrated</span>  

- **Data Aggregation:** Combined and summarized transactional records by product.  
- **Advanced Group By:** Used Power Query’s Advanced Group By feature to create multiple calculated fields simultaneously.  
- **Custom Column Logic:** Applied the `Text.Combine()` function for dynamic list merging.  
- **Data Transformation Workflow:** Built an end-to-end ETL process from raw CSV to structured output.  
- **Analytical Thinking:** Simulated a real-world retail analytics scenario — connecting products to their buyers.  
- **Excel Integration:** Leveraged Excel as the final reporting medium for presenting clean, summarized data.  

---

## <span id="tools-used">🛠 Tools Used</span>  

- **Microsoft Power Query** — For data import, transformation, grouping, and aggregation.  
- **Microsoft Excel** — For output visualization and result presentation.  
- **ChatGPT** — For generating the initial dataset structure.  

---

## <span id="project-outcome">📊 Project Outcome</span>  

✅ Created a concise and meaningful summary table with unique products.  
✅ Automated calculation of purchase frequency for each product.  
✅ Combined all related customers into a single cell for easy readability.  
✅ Enabled faster insights into which customers buy which products most frequently.  
✅ Enhanced practical understanding of Advanced Grouping and Data Aggregation in Power Query.  

The final result was a **clean, analysis-ready dataset** suitable for product-customer analytics, dashboards, and BI reporting workflows.  

---

## <span id="repo-contents">📂 Repository Contents</span>  

| File / Folder | Description |
|----------------|-------------|
| `Advanced Product Customer Grouping Analysis.xlsx` | Main Excel workbook with Power Query transformations. |
| `SampleData.csv` | Raw data file generated for the project. |
| `Project Documentation.pdf` | Step-by-step project explanation and logic breakdown. |
| `Power Query Formula.png` | Snapshot of the custom formula used for combining customer names. |
| `Final Output Preview.png` | Image showing the cleaned and summarized final dataset. |

---

## <span id="project-use">🚀 How to Use This Project</span>  

1. **Download or Clone** this repository.  
2. Open `Advanced Product Customer Grouping Analysis.xlsx`.  
3. Go to **Data tab → Queries & Connections** to explore Power Query steps.  
4. To test with your own data:  

   - Replace the source CSV file with your dataset (same column headers).  
   - Refresh the Power Query connection.  

5. View the **transformed and grouped result** in the Excel output sheet.  

---

## <span id="future-enhancements">🌟 Future Enhancements</span>  

- Integrate this grouping logic with **Power BI** to create visual dashboards.  
- Add dynamic filters for **date ranges**, **cities**, or **payment modes**.  
- Incorporate **sales trend analysis** and **customer segmentation visuals**.  
- Build an **automated Power Query refresh** for continuous data updates.  

---

## <span id="contact">📬 Connect with Me</span>  

📧 **Email:** [rajeevtiwari8055@gmail.com](mailto:rajeevtiwari8055@gmail.com)  
💻 **GitHub:** [github.com/rajeevgit8055hub](https://github.com/rajeevgit8055hub)  
🔗 **LinkedIn:** [linkedin.com/in/rajeev-tiwari123](https://linkedin.com/in/rajeev-tiwari123)  
🌐 **Website:** [rajeevgit8055hub.github.io/rajeevtiwari.github.io](https://rajeevgit8055hub.github.io/rajeevtiwari.github.io)  

🤝 *Thanks for visiting my profile!*  

---

## <span id="project-visual">📷 Project Snapshot</span>  

![Advanced Product Customer Grouping Analysis](Project%20Overview.png)

---


