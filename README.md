# n8n Automations 🚀

This repository contains a collection of automation workflows built with [n8n](https://n8n.io/).  

### 1. Lead Capture & Notification (Form → Google Sheets + Email)
**Description:** Automates lead management by capturing form submissions, saving them into Google Sheets as a centralized database, and instantly sending an email alert with the lead’s details. This ensures no potential lead is missed and the team can follow up quickly.

**Screenshot:**  
![Google Sheets Workflow](./screenshots/automation1.png)

### 2. Real Estate Client Automation (Google Sheets + API → Dynamic Email)
**Description:** Streamlines client onboarding for a real estate workflow. When new client data (ID, Name, Number, Budget) is submitted:  
1. Gender is predicted using **Genderize.io** based on the name.  
2. Nationality is predicted using **Nationalize.io** based on the name.  
3. The calculated Gender and Nationality are appended to the Google Sheet along with original client data.  
4. A dynamic email is sent to notify the team about the new client with all details included.  

**Screenshot:**  
![Real Estate Workflow](./screenshots/automation2.png)
