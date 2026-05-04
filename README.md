# IT23832480 – IT3040 Assignment 1



##  Project Title

Automated Testing for Singlish to Sinhala Transliteration System



##  Repository

https://github.com/SandaniChamoda/IT23832480_IT3040_Assignment1



---  


## Project Structure

IT23832480/

- IT23832480_test_automation.py → Playwright automation script

- IT23832480_Assignment 1 - Test cases.xlsx → Excel file with test cases and results

- IT23832480_requirements.txt → Python dependencies

- IT23832480_README.md → Project documentation

---



## Prerequisites



- Python 3.8 or higher  

- Internet connection  



---



##  Technologies Used



- Python  

- Playwright (Python UI Automation)  

- OpenPyXL (Excel handling)



---



##  How to Run the Project



1. Open terminal inside project folder  



2. (Optional) Activate virtual environment  

venv\Scripts\activate  



3. Install dependencies  

pip install -r requirements.txt  

playwright install  



4. Run the automation script  

python IT23832480_test_automation.py --excel "IT23832480_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open


---



##  Output



- Results are automatically written to the Excel file  

- Columns updated:

- Actual output  

- Status (PASS / FAIL)  



---



##  Test Case Details



- Total Test Cases: 50+  

- Test Type: Negative Testing  



### Covered Scenarios:

- Mixed language inputs (Singlish + English)  

- Spelling variations  

- Emojis & symbols  

- Real-world scenarios (banking, travel, apps)  

- System-related messages (errors, logs)  

- Numeric and date inputs  



---



##  Important Notes



- This system uses strict comparison  

- Even small differences in Sinhala output (spacing, formatting, spelling) will result in FAIL  

- Some failures are expected due to:

- Transliteration inconsistencies  

- Mixed language complexity  

- UI timing delays  

- The system requires an active internet connection to access the transliteration website



---



##  Student Information



- Student ID: IT23832480

- Module: IT3040  

- Assignment: Assignment 1 (Option 1)  



---



##  Final Status



✔ Automation script working  

✔ Excel-based validation completed  

✔ Test coverage includes multiple edge cases  



---



##  Submission Notes



- Virtual environment (venv) is excluded from submission  

- All required files are included  

- Project is fully runnable using requirements.txt  



---

## Author



IT23832480

---
