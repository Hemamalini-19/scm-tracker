📦 Supply Chain Lead Time & Reliability Analytics
Project Overview
This project focuses on optimizing supply chain operations through data-driven performance tracking. It provides a Python-based automated pipeline to monitor Purchase Orders (POs) and identify lead time variances. By transforming raw logistics data into actionable insights, this tool helps prevent stockouts and improves procurement planning.

🛠 Key Functionalities
Data Cleansing & Validation: Processes raw CSV exports to ensure data integrity for ERP system integration.
Lead Time Logic: Automatically calculates the delta between "Expected Delivery" and "Actual Delivery" dates.
Performance Reporting: Groups data by vendor to calculate average delay days and reliability percentages.
Visual Analytics: Generates automated bar charts for trend analysis and stakeholder reporting.


📊 Technical Schema
The analysis utilizes a standard SCM data structure:
po_number: Unique Purchase Order identifier.
vendor_name: Name of the manufacturing or logistics partner.
expected_date: The scheduled arrival date.
actual_date: The date the shipment was officially received and logged.

💻 Tech Stack & Tools
Languages: Python (Pandas) for core data manipulation.
Visualization: Matplotlib & Seaborn for generating performance dashboards.
version Control: Git/GitHub for professional code management and documentation.
Environment: Cloud-based execution via Google Colab.

📈 Professional Impact
Operational Efficiency: Reduces manual oversight by automating the tracking of open orders.
Decision Support: Identifies high-risk vendors, allowing for proactive adjustments to safety stock levels.
Data Integrity: Implements a structured workflow to maintain "clean" master data records.
