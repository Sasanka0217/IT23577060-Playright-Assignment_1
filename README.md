# IT23577060-Playright-Assignment_1
#  ITPM Assignment 1 - Singlish to Sinhala Transliteration Testing
###  Student Name: PATHIRANA R.P.S.M
###  Registration Number: IT23577060

##  Project Description

## 🧪 Test Automation for Sinhala Transliteration

This project automates the testing of Sinhala transliteration and translation web applications using **Python + Playwright**. It reads test cases from an Excel file, inputs Singlish text into the web UI, captures the Sinhala output, and compares it with the expected result.

---

## 📌 Features

* ✅ Automated UI testing using Playwright
* ✅ Reads test cases from Excel (`.xlsx`)
* ✅ Automatically:

  * Inputs text
  * Captures output
  * Compares with expected result
  * Marks **PASS / FAIL**
* ✅ Writes results back to Excel
* ✅ Handles dynamic UI and retries

---

## 🛠️ Technologies Used

* Python 3
* Playwright
* OpenPyXL

---

## 📂 Project Structure

```
IT23577060-Playright-Assignment_1/
│
├── it23577060_test_automation.py
├── it23577060_Assignment 1 - Test cases.xlsx
└── README.md
```

---

## 📊 Excel Format

Your Excel file should contain columns like:

| TC ID | Input (Singlish) | Expected Output (Sinhala) | Actual Output | Status |
| ----- | ---------------- | ------------------------- | ------------- | ------ |

* **Input** → Text sent to the website
* **Expected Output** → Correct Sinhala result
* **Actual Output** → Filled by script
* **Status** → PASS / FAIL

---

## ⚙️ Setup Instructions

### 1. Install Python

Make sure Python is installed:

```
py --version
```

### 2. Install Dependencies

```
pip install playwright openpyxl
playwright install
```

---

## ▶️ How to Run

### 🔹 For Chat Translator

```
py it23577060_test_automation.py --excel "it23566798_test_automation/it23577060_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 800 --save-every 1 --keep-open
```

---

## ⚠️ Important Notes

* ❗ Make sure the Excel file is **closed** before running
* ❗ Use correct column names (Input / Expected Output)
* ❗ Internet connection is required
* ❗ Some failures may occur due to API issues (e.g., *Failed to fetch*)

---

## 🧠 How It Works

1. Reads test cases from Excel
2. Opens browser using Playwright
3. Inputs Singlish text into UI
4. Clicks Translate/Transliterate button
5. Captures Sinhala output
6. Compares with expected output
7. Writes results back to Excel


---

## 👨‍💻 Author

Sasanka Pathirana

---

