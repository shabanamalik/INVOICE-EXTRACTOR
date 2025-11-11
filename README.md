https://youtu.be/v2mJSgYlkoo
# INVOICE-EXTRACTOR
AI-powered Invoice Information Extractor built in n8n using Google Gemini AI. Automatically reads invoice PDFs from Google Drive, extracts key details (invoice no., date, amount), saves them in Google Sheets, and sends confirmation via Gmail — saving time and reducing manual errors. 🚀
# 🧾 AI Invoice Information Extractor  
An intelligent automation workflow built in **n8n** using **Google Gemini AI**, designed to extract key details from invoices automatically, store them in Google Sheets, and send confirmation emails — eliminating manual effort and human error.

---

## 🎯 Purpose  
The purpose of this project is to automate the process of invoice data management.  
Instead of manually reading each PDF invoice and entering data into spreadsheets, this workflow automatically:  
- Reads the uploaded invoice from Google Drive  
- Extracts all key information (Invoice No., Date, Amount, Vendor Name)  
- Saves the structured data into Google Sheets  
- Sends an automated email confirmation  

This saves time, reduces manual errors, and keeps records organized for businesses, freelancers, and finance teams.

---

## 🚀 Benefits  
✅ **Time-Saving:** Instantly processes invoices without human input.  
✅ **Error-Free Records:** Eliminates manual entry mistakes.  
✅ **Centralized Storage:** Keeps all invoices organized in Google Sheets.  
✅ **Real-Time Updates:** Sends confirmation emails after each invoice is processed.  
✅ **Scalable:** Works for any business size or number of invoices.

---

## ⚙️ Workflow Overview  

### 📂 Nodes Used and Their Purpose

1. **Google Drive Trigger**  
   - Watches a specific folder for new invoice uploads.  
   - Automatically starts the workflow when a new PDF is added.

2. **Download File (Google Drive)**  
   - Downloads the uploaded invoice PDF for processing.  

3. **Extract from File (n8n PDF Extractor)**  
   - Reads and extracts text content from the invoice file.  

4. **Information Extractor (Google Gemini Model)**  
   - Uses AI to understand the text and extract structured data like invoice number, date, amount, and vendor name.  

5. **Append Row (Google Sheets)**  
   - Saves the extracted information in a Google Sheet for record keeping.  

6. **Message a Model (AI Summarizer)**  
   - Generates a clean summary or message confirming that the invoice has been successfully processed.  

7. **Send Message (Gmail)**  
   - Sends the AI-generated confirmation email to the user or team.  

---

## 🧩 Tools & Integrations  
| Tool | Purpose |
|------|----------|
| **n8n** | Workflow automation platform |
| **Google Drive** | Invoice storage and trigger |
| **Google Gemini AI** | Extracts and interprets text |
| **Google Sheets** | Stores structured data |
| **Gmail** | Sends confirmation emails |

---

## 💡 Example Use Case  
When a new invoice PDF is uploaded to your Google Drive folder, the workflow automatically extracts details like **Invoice #, Date, and Total Amount**, saves them in a Google Sheet, and sends an instant email saying *“New Invoice Processed Successfully.”*  

---

## 🌟 Outcome  
A fully automated AI-powered invoice processing system that simplifies financial record management — saving time, minimizing errors, and improving productivity for any business. 🚀
