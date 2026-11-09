# DemoPoint CRM Portfolio Project

**Contact Data Preparation | Sales Pipeline Management | HubSpot Reporting**

## Project overview

DemoPoint Business Services is a fictional business used for a hands-on CRM portfolio project. The project covers preparing a contact dataset in Microsoft Excel, importing customer records into HubSpot CRM, organizing sales deals, creating follow-up tasks, recording an interaction note, and building a sales performance dashboard.

The purpose was to practise an end-to-end CRM workflow, from contact data preparation to sales reporting. All customer information, deal activity, and financial figures in this project are simulated.

## Tools used

- **Microsoft Excel:** Data inspection, duplicate checks, data cleaning, import-status review, and Data Quality Log.
- **CSV:** Prepared datasets for contact and deal imports.
- **HubSpot CRM:** Contact management, deal pipeline management, record associations, tasks, activity notes, and reporting.
- **Visual Studio Code, Git, and GitHub:** Project organization and version control.

## Project workflow

### 1. Contact data preparation

The Excel workbook contains four sheets: `Start Here`, `Raw Contacts`, `Working Copy`, and `Data Quality Log`. The exercise began with **50 synthetic contact records**.

In the Working Copy, I reviewed duplicate customer entries, missing email addresses, blank job titles, and formatting inconsistencies. The working dataset contains **48 records** after removing two redundant entries. **Three contacts were held from import because their email field was missing**, while two contacts with blank optional job titles were retained. I prepared the final contact import CSV with **45 records**.

The Data Quality Log documents the quality checks and decisions made during preparation.

### 2. Contact import into HubSpot

I imported the prepared **45-contact CSV** into a dedicated DemoPoint HubSpot workspace. The resulting contact records formed the basis for the sales pipeline exercise.

### 3. Sales pipeline setup and deal management

I created **three deals manually (DP-001 to DP-003)**, then imported **12 additional deals (DP-004 to DP-015)** from a CSV file and associated them with existing contacts using their email addresses.

The deals cover different stages of the sales process, including appointment scheduling, qualification, presentation, decision-making, contract sent, Closed Won, and Closed Lost. I also reviewed deal amounts and close dates in HubSpot.

### 4. Follow-up tasks and customer interaction records

I created **three follow-up tasks** associated with contact records for Peter Njoroge, Fatima Ali, and John Ochieng. I also recorded a practice interaction note on the **DP-006 Premium Package** deal to demonstrate how activity details can be documented against a CRM record.

### 5. Sales reporting dashboard

I created the **DemoPoint – CRM Sales Performance** dashboard with two HubSpot reports:

1. **DemoPoint – Deals by Stage** — a view of the sales pipeline and deal counts.
2. **Closed revenue by month with deal total and closed revenue breakdown** — a monthly view of simulated closed-won deal value.

The dashboard screenshot shows **15 deals** and **three closed-won deals totaling $53,000**, using the currency displayed by the HubSpot workspace. These figures represent simulated opportunities, not real customer payments or business revenue.

## Project results

| Measure | Result |
|---|---:|
| Initial contact records | 50 |
| Records in the Working Copy | 48 |
| Contacts prepared and imported | 45 |
| Deals created manually | 3 |
| Deals imported from CSV | 12 |
| Total deals tracked | 15 |
| Open deals | 9 |
| Closed Won deals | 3 |
| Closed Lost deals | 3 |
| Simulated closed-won deal value shown in HubSpot | $53,000 |
| Follow-up tasks created | 3 |
| Dashboard reports | 2 |


## Project files

| File | Contents |
|---|---|
| [Data Cleaning Workbook](DemoPoint_CRM_Data_Cleaning_Workbook.xlsx) | Excel data preparation and Data Quality Log |
| [Clean Contacts CSV](CRM_Clean_Contacts.csv) | 45 prepared contacts |
| [Deals CSV](DemoPoint_Deals_DP004_DP015.csv) | 12 imported sales deals |
| [Sales Pipeline Overview](Sales%20Pipeline%20Overview.png) | Deal stages and sales pipeline |
| [Deal Activity and Interaction Note](Deal%20Activity%20and%20Interaction%20Note.png) | CRM interaction documentation |
| [Customer Follow-Up Tasks](Customer%20Follow-Up%20Tasks.png) | Contact follow-up tasks |
| [CRM Sales Performance Dashboard](CRM%20Sales%20Performance%20Dashboard.png) | Sales performance reports |


## Dashboard preview

![DemoPoint CRM Sales Performance Dashboard](CRM%20Sales%20Performance%20Dashboard.png)

## Skills demonstrated

This project demonstrates contact data preparation, spreadsheet data-quality checks, CSV imports, CRM record management, contact-to-deal associations, follow-up task tracking, interaction documentation, and dashboard-based pipeline reporting.

**Note:** DemoPoint is a training scenario with fictional contacts and simulated sales activity. This repository documents a practical learning project, not paid client work or a live commercial CRM.
