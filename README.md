# Job Application Saver

A powerful tool to streamline your job application process by saving LinkedIn job postings as PDFs and organizing them in an Excel file. Designed with an intuitive GUI, this tool helps you keep track of your applications efficiently.

---

## Features
- **Clean and validate LinkedIn job URLs**: Automatically processes and verifies job posting URLs.
- **Save job postings as PDFs**: Download job postings directly in a formatted PDF.
- **Organized Excel record**: Automatically updates an Excel file with job details, including company name, job title, and links.
- **Duplicate Detection**: Prevents duplicate entries and allows user confirmation to avoid redundancy.
- **Automatic Archiving**: Archives older job postings and updates records after 30 days.

---

## Download
Click below to download the latest version of the executable:
- [Download Job Application Saver](https://github.com/Bjohns800/job-application-saver/releases/latest)

---

## Application requirements
you must have **Google Chrome** installed and logged into your personal linkedin acocunt, as the software uses Chrome to access the internet.

---

### Requirements
- **Python 3.8+**
- The following Python libraries (install with `pip`):
  - selenium
  - openpyxl
  - tk
  - webdriver-manager

---

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Bjohns800/job-application-saver.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run theApplication:

   ```bash
   python src/job_application_saver_app.py
   ```

---

## Usage

1. Launch the application (either by running the `.exe` file or the Python script).
2. Paste a LinkedIn job URL into the input field.
3. Click **Go** to:
  -Save the job posting as a PDF.
  -Add its details to the Excel file.
4. Review your organized job records in the Excel sheet or open individual PDFs.

---

##Excel File Columns
- **Date and Time**
- **Company Name**
- **Job Title**
- **PDF Link** (hyperlink)
- **LinkedIn URL** (hyperlink)
- **Archived Tick**
- Additional predefined columns for metadata to be input by the user:
  - **Location**
  - **In Person**
  - **Sector**
  - **Status**
  - **Notes**

---

### Screenshot






---

## Contributing

1. **Fork the repository**:
   - Click the **Fork** button on the top right of the repository page.

2. **Create a new feature branch**:
   ```bash
   git checkout -b feature-branch
   ```
   
3. **Commit your changes**:
   ```bash
   git commit -m "Add feature XYZ"
   ```
   
4. **Push to your fork**:
  ```bash
  git push origin feature-branch
  ```

5. **Submit a pull request**:
   -Go to the original repository and click on **New Pull Request**.
   -Select your branch and submit the pull request to the `main` branch.

---

## Future Plans
  - Support for additional job boards (e.g., Glassdoor, Indeed) and companies direct websites.
  - Fix of bug where time is added to spreadsheet in wrong format.

   
   

