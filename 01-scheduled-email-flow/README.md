# 01 — Scheduled Email Flow 📧

## 🔍 What Problem Does This Solve?
Imagine a company like Contoso hosts an annual event.
People call in and leave their contact details in an Excel sheet.
Instead of someone manually emailing each person every day,
this flow does it **automatically** — every single day, on schedule.

## 🛠️ What I Built
A **Scheduled Cloud Flow** in Microsoft Power Automate that:

1. ⏰ Runs automatically **every day at a set time**
2. 📊 Reads contact rows from an **Excel file stored on OneDrive**
3. 📧 Sends a **personalized email** to each contact automatically

## 🔧 Tools Used
- Microsoft Power Automate
- Microsoft Excel (OneDrive)
- Outlook (Email connector)

## 🧠 Flow Structure

| Step | Type | What it does |
|------|------|--------------|
| 1 | Trigger — Recurrence | Starts the flow every day |
| 2 | Action — List rows (Excel) | Gets all contacts from the Excel table |
| 3 | Action — For Each loop | Loops through every contact row |
| 4 | Action — Send an Email | Sends personalized email to each contact |

## 💡 What I Learned
- How to use the **Recurrence trigger** to schedule automation
- How to connect Power Automate to **Excel on OneDrive**
- How to use **Dynamic Content** to personalize emails
- How a **For Each loop** works in Power Automate

## 📚 Source
Built by following:
[Microsoft Learn — Create recurring flows](https://learn.microsoft.com/en-us/training/modules/get-started-flows/6-flow-scheduled-flows)

## 📅 Date Completed
April 2026
