# Excel-to-Web-Form-Automation
-This is Automation where with the help of MS Power Automate a automation is done to do data entry form excel to webform.

# Excel to Web Form Automation using Microsoft Power Automate Desktop

## 📌 Overview

This project automates the process of reading data from an Excel spreadsheet and entering it into a web-based form using **Microsoft Power Automate Desktop (PAD)**. The automation eliminates repetitive manual data entry, improves accuracy, and saves time.

## 🚀 Features

* Reads records from an Excel workbook.
* Launches a web browser automatically.
* Navigates to the target web form.
* Populates web form fields with data from Excel.
* Submits the form for each record.
* Handles multiple rows of data in a loop.
* Includes basic error handling and logging.

## 🛠️ Technologies Used

* **Microsoft Power Automate Desktop**
* **Microsoft Excel**
* **Web Automation**
* **UI Automation**

## 📂 Project Structure

```text
├── Flow/
│   └── Power Automate Desktop Flow
├── Input/
│   └── Desk.xlsx
|   └── IssueDesc.xlsx
├── Screenshots/
│   └── Screenshots of the flow
└── README.md
```

## 📋 Prerequisites

Before running the automation, ensure you have:

* Microsoft Power Automate Desktop installed.
* Microsoft Excel installed.
* Access to the target web application.
* Appropriate permissions to submit data through the web form.

## ⚙️ How It Works

1. Open the Power Automate Desktop flow.
2. Launch the automation.
3. The flow opens the Excel file.
4. Reads each row from the worksheet.
5. Opens the target web application.
6. Maps Excel columns to the corresponding web form fields.
7. Enters the data into the form.
8. Submits the form.
9. Repeats the process until all records are processed.
10. Closes the Excel application and completes the execution.

## 📊 Sample Data Format

| category   | Sub category                                | AssetCode     | Description    |
| ---------- | ------------------------------------------- | ----------    | --------       |
|PC          | Network issue                               | ABC/123/PC | Network is not working, unable to open any website |
|PC          | PRinter issue                               | ABC/145/PC | Printouts are not coming properly |

> **Note:** Modify the Excel columns to match your web form fields.

## 🔧 Configuration

Before execution, update the following if required:

* Excel file path
* Target website URL
* Web element selectors (if the web page changes)
* Input worksheet name


## 📸 Screenshots

You can add screenshots of:

* Power Automate Desktop Flow
* Excel Input File
* Target Web Form
* Successful Execution

## 📈 Benefits

* Reduces manual effort
* Improves data accuracy
* Faster processing
* Easy to maintain
* Scalable for larger datasets

## 🔮 Future Enhancements

* Dynamic field mapping
* Validation before submission
* Detailed execution logs
* Email notification after completion
* Database integration
* Support for multiple web forms

## 🤝 Contributing

Contributions, improvements, and suggestions are welcome. Feel free to fork the repository and submit a pull request.

## 📄 License

This project is available under the MIT License.

---

**Author:** *Your Name*

If you found this project useful, consider giving it a ⭐ on GitHub.
