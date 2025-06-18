# 🧾 Update Invoice with Discount Code

This automation was built as part of the Studio Web course module on data entry automation.

## 📌 Use Case

When an email arrives from a specific sender, the automation:

1. Downloads the invoice attachment
2. Uploads the file to OneDrive or Google Drive
3. Extracts the client code from the spreadsheet
4. Uses a web portal (ACME System 1) to check for a matching discount
5. Inserts the discount into the invoice
6. Sends the updated invoice back via email

## 💡 Key Concepts Applied

- Trigger-based automation (`Email Received`)
- File handling in Gmail, Google Drive, and OneDrive
- Excel automation: reading and writing cells
- Browser automation with `Use Browser` activity
- Anchor targeting with target + anchor configuration
- End-to-end test run with successful execution logs

## 📸 Visual Steps

| Step | Description |
|------|-------------|
| 1    | Download invoice attachments from incoming emails |
| 2    | Upload files to the designated OneDrive folder |
| 3    | Extract client code from invoice |
| 4    | Retrieve discount info from ACME portal |
| 5    | Update the invoice with discount |
| 6    | Send email with updated invoice attached |

---

## 📁 Folder Includes

- `README.md`
- Visual Steps PDF
- Automation Execution Video
- Screenshots – automation steps and final result
  
