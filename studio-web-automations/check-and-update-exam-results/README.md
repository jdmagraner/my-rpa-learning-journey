# 📊 Exam Results Notification Bot

This project was built as part of my RPA learning path on UiPath Academy — specifically for the lesson **"How to handle errors in Studio Web"**.

## 🧠 Use Case
The automation reads a spreadsheet of candidate names, emails, and exam scores, and sends a customized email based on the result:

• If the candidate is marked as **Absent**, send a message notifying them of no available exam data  
• If the score is **45 or higher**, send a congratulatory email  
• If the score is **below 45**, send an encouragement to try again next time

This solution demonstrates:
• Conditional logic using nested **If** activities  
• Real-time value parsing using `Double.Parse()`  
• Composing dynamic emails with variable-based personalization  
• Error handling strategies like breakpoints and watch panel usage  
• End-to-end testing of multiple outcomes via mock spreadsheet data

## 🧪 Workflow Highlights
• ✅ **Manual Trigger** kicks off the process  
• ✅ **For Each Row in Spreadsheet** loops through all entries  
• ✅ **Nested If conditions** handle pass/fail/absent logic  
• ✅ **Dynamic Gmail drafts** generated with personalized subject lines and messages  
• ✅ Includes setup for Google Workspace (also available for Microsoft 365)

## 🧰 Files Included
• `Check and update exam results solution - Google Workspace.uip`  
• `Check and update exam results solution - Microsoft Office 365.uip`  
• Automation screenshots (in `/screenshots/`)  

## 🙌 Lessons Learned
Working with multiple branches and testing them with breakpoints helped me feel more confident troubleshooting my bots. I also practiced using the **Watch panel** to monitor key variables like `Marks` and `Email` step by step.

---
