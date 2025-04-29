# 🔐 Cybersecurity Analysis Power BI Dashboard

A comprehensive Power BI dashboard for cybersecurity analysis, enabling security teams to monitor threats, detect anomalies, and respond effectively using data-driven insights.

## 📊 Project Overview

This repository contains Power BI dashboards and supporting assets designed to visualize and analyze key cybersecurity metrics. The dashboard leverages data from various security logs  to identify devices and systems affected, number of infected files and types of attcks, and assess risk exposure and vulnerabilites in an organization.

## 🚀 Features

- ✅ Real-time threat detection visualization
- 🔎 Interactive filters for deep-dive analysis (by attack type, ports, severities etc.)
- 📌 Summary KPIs: Numbers of Devices, Infected files, affected systems, attack types and ports etc etc.
- 📂 Drill-through to detailed threat logs


## Tools used
- Jupyter notebook to access and clean the data sets.
- Microsft Power BI for dashboard creation
- Power Query for data transformation in Microsoft Power BI
- DAX for advanced calculations in Microsoft Power BI

### Steps
- Step 1a :Load data to python for cleaning prior to analysis.
- Step 1b : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was further cross-examined and it was observed that  in none of the columns; errors & empty values were present.
- Step 5 : The model view was used to explore the connection amoongst the various datasets for analysis.
-Step 6 : Varoius measures were created using DAX expressions to aid analysis such as "Device ID", "Infected files", "Affected sytem", "Ports", "Attack types", "Protocols".
- Step  7: In the report view, under the view tab, theme was selected.
- Step 8 : Multiple card visuals were added to the canvas repersenting the measures created in step 6.
- Step 9 : Page 1 of the dashboard shows an overview of the distribution of the infected files and attack types while page 2 shows an overview of the severity distribution
- Step 10 : Various charts and graphs were added to the canvas; each used to visualise a set of the analysis. 

## Key Insights
-	Attack type by Detection Status = 70.26% of the attack type were detected while 29.74% were partially detected or non-detected
-	Infected files by detection status = 70.51% of the infected files were detected while 29.49% were partially detected or non-detected
-	There was an even distribution of the attack type across the various operating systems with Cisco OS having most of the attacks at 20.31%
-	Attack type by protocol = ICMP protocol had most of the attack at 69.84%
-	Attack type by systems = Most of the systems were attacked by trojan(19.41%) and ransomware(15.26%)
-	70.26% of the severity of the attacks were detected.
-	Server (20.64%) and Router (20.03%) asset types had the most severe attacks.
-	Most of the attacks were ranked by severity as medium (39.79%) and high 30.65%)


## 📷 Dashboard Preview
[Image](https://github.com/user-attachments/assets/473ec699-8011-4fd8-9a6e-759ba4210b7c)

[Image](https://github.com/user-attachments/assets/5861fb2c-459c-4bbb-b7f3-58827dcc8142)




