# 🏥 Healthcare Lab Diagnosis TAT & Analytics Engineering
> **An End-to-End Analytics Project optimizing Laboratory Turnaround Time (TAT) using Excel Data Modeling, Advanced SQL Querying, and Executive Power BI Dashboarding.**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

---

## 👁️ 1. Executive Dashboard Preview (The Hero Visual)
*Designed a Premium Neon-Glow Monochromatic Blue Dashboard with standard layouts, 3D shadows, and a structured left navigation filter panel for seamless executive tracking.*

<img width="1170" height="647" alt="image" src="https://github.com/user-attachments/assets/35f46b7a-9b26-4f5a-ae76-fbcfa2108a98" />


---

## 📊 2. Data Architecture & Excel Modeling
Before moving to database engineering, I simulated and structurally modeled a comprehensive clinical dataset containing critical healthcare parameters.

### 🧠 Core Business Logic & Metrics Engineered:
* **Dynamic Mapping:** Used `VLOOKUP` to map standard department-wise target benchmarks dynamically.
* **Automated Data Quality & Error Checks:** Built logical nested `IF` statements to capture systemic pipeline errors and log anomalies.
* **Status Automation:** Applied conditional arrays (`IF`) to automate `On Time` vs `Delayed` status tracking.
* **Visual Alerts:** Leveraged **Conditional Formatting** to instantly flag high-priority duplicate `Data Quality IDs` and `Delayed` emergency statuses.
* **KPI Framework:** Created Pivot-driven analysis sheets mapping `Min vs Max Actual TAT` metrics and total test volume across departments.

<img width="1156" height="657" alt="image" src="https://github.com/user-attachments/assets/38143dea-4d25-41f3-9c77-acc7f54f1e84" />
<img width="343" height="187" alt="image" src="https://github.com/user-attachments/assets/26ccc43a-5340-42e0-8dc3-92c57f0ebcc4" />
<img width="606" height="177" alt="image" src="https://github.com/user-attachments/assets/030b304b-b2a9-420c-9d08-837043f50427" />
<img width="489" height="187" alt="image" src="https://github.com/user-attachments/assets/9035d91f-b183-42f5-acf3-f8e48c5ae0bd" />
<img width="1072" height="513" alt="image" src="https://github.com/user-attachments/assets/cb6ca877-597d-4b8f-911a-4f1b76c33323" />

## 🗄️ 3. Database Engineering & Advanced SQL Queries
The modeled dataset was structured and imported into SQL to perform rigorous data quality audits and operational bottleneck detection.

### 🔍 Q1: High-Priority Emergency (Stat) Tests experiencing Delays
* **Objective:** Capture critical workflow leaks requiring immediate management attention.
<img width="479" height="372" alt="image" src="https://github.com/user-attachments/assets/f0e04c99-aec3-426a-bcc1-d98e3d9db17a" />


​🕒 Q2: Average Testing Time (TAT) by Department (Granular Analysis)
​Objective: Identify which clinical departments are running slower than operational targets.
<img width="442" height="378" alt="image" src="https://github.com/user-attachments/assets/ad7d9758-1572-4604-ace2-d6b6464815d5" />


​🚨 Q3: Duplicate Records Alert & Pipeline Integrity Audit
​Objective: Data Quality Check to prevent duplicate billing or ghost entries.
<img width="411" height="230" alt="image" src="https://github.com/user-attachments/assets/a1db4ec3-ab43-48d9-968f-e596591682e2" />

Q4: Outlier Anomaly Detection & Data Quality Check
​Objective: Instantly isolate system errors or manual entry bugs where the logged processing time is impossible (\le 0 hours) or critically high (>100 hours).
<img width="387" height="95" alt="image" src="https://github.com/user-attachments/assets/78bec989-ec72-4ad4-8e45-0936657ddeb0" />














---

