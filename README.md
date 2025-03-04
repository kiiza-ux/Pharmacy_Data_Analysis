
# **Pharmacy Dispensing Analysis – Mawenzi Regional Referral Hospital**  

## **Project Overview**  
This project analyzes **pharmacy dispensing trends** at **Mawenzi Regional Referral Hospital**, using data extracted from the **Afya EHMS** (Electronic Health Management System). The analysis explores **medication utilization, patient demographics, insurance coverage (NHIF vs. Cash), and dispensing trends over time**. The insights gained can aid in **inventory optimization, resource allocation, and policy decision-making** to enhance pharmaceutical services.  

## **Objectives**  
🔹 **Identify the most dispensed medications** to guide procurement and stock management.  
🔹 **Analyze dispensing trends over time** to detect seasonal patterns and variations.  
🔹 **Examine patient demographics (age, gender, clinic type)** to understand healthcare demand.  .  
🔹 **Investigate the utilization of non-drug medical items** (e.g., syringes, IV fluids).  
🔹 **Provide actionable recommendations** for improving hospital pharmacy operations.  

## **Dataset Overview**  
The dataset consists of **123,944 records**, capturing details of dispensed medications and patient transactions.  

### **Key Columns:**  
- **Patient_ID** – Unique identifier for each patient.  
- **Age & Gender** – Patient demographics.  
- **Date_Dispensed** – Date of medication issuance.  
- **Clinic_Type** – The hospital department where the medication was dispensed (e.g., Emergency, General, Orthopedic).  
- **Item_Name** – Name of the **dispensed medication or medical supply**.  
- **Quantity_Dispensed** – Total units of the item issued.  
- **Sponsor** – **Payment type**:  
  - **Cash** – Patients paying out-of-pocket.  
  - **NHIF** – Patients covered by **National Health Insurance Fund**.  
- **Subtotal** – Total cost of the dispensed item(s).  

## **Key Findings**  
**Most Dispensed Medications:** Identified top drugs in high demand.  
**Age Group Trends:** Young adults (20-39) have high antipsychotic usage, possibly linked to mental health trends.  
**Seasonal Fluctuations:** Patient visits dropped after July due to **the opening of additional departments (Orthopedic & Community Pharmacy), redistributing patient load**.    

## **Technologies Used**  
**Python (Pandas, Matplotlib, Seaborn, Plotly)** for data analysis & visualization.  
**Jupyter Notebook** for interactive exploration.  
**Git & GitHub** for version control and collaboration.  

## **How to Use This Repository**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/kiiza-ux/Pharmacy-Data-Analysis.git
   ```  
2. Install dependencies:  
   ```bash
   pip install pandas matplotlib seaborn plotly
   ```  
3. Open and run the **Jupyter Notebook (`.ipynb`)** for insights.  

