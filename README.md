


# JobScrapper

**Overview:**
JobScrapper is a Python-based job search automation tool that allows users to search and export job listings from multiple job boards (Indeed, LinkedIn, Google, Bayt, and more) for a wide range of countries and job types. The script features update checking, notifications for errors and usage, and a built-in updater utility.

**Note:** The selling or sharing of this code without direct permission is prohibited and will be met with consequences.
**Note:** The source code for this script will not be made publicly available; however, script is usable by exe.

![job-scraper](https://github.com/user-attachments/assets/ce8232be-b7c1-403a-8007-bf8604149168)

**Warning:** This tool is intended for educational and research purposes only. The author does not encourage or endorse misuse. By using this tool, you accept full responsibility for your actions and compliance with job board terms of service and applicable laws. The author is not liable for any consequences, including account bans or legal issues. Use at your own risk.

## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [How the Code Works](#how-the-code-works)
- [Updater Utility](#updater-utility)
- [Supported Countries for Job Searching](#supported-countries-for-job-searching)
- [Notes](#notes)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)

## Requirements
Most requirements are pre-installed, but if errors occur, install the following:
- Python 3.x
- jobspy library
- requests library

## Installation
1. **Sharing or Selling without Permission:**
   The selling or sharing of this code without direct permission is prohibited and will be met with consequences.
2. **Install jobscrapper.exe:**
   Download and use the provided executable for ease of use.
3. **Check Anti Virus:**
    ```bash
    Settings
    Update and Security
    Windows Security
    Open Windows Security
    Virus and Threat Protection
    Protection History
    Then Allow most recent if it containts "jobscraper" or "updater"
    ```
## Usage
1. Download the files from the repository.
2. Double click `jobscrapper.exe` to launch, or run the script with Python.
3. Enter the job title, city, country, job type, number of results, and job posting age when prompted.
4. The script will search supported job boards and export results to a excel file(CSV).
5. Progress and status messages will be printed in the terminal.

## How the Code Works
- **Startup & Update Check:**
    - Checks for updates using a remote version file. If a new version is available, downloads and launches the updater.
- **Error & Usage Tracking:**
    - Sends error and usage notifications
- **User Prompts:**
    - Prompts for job search criteria (title, city, country, job type, etc.).
- **Export:**
    - Saves results to a CSV file, auto-incrementing the filename if needed.
- **Exit:**
    - Prints completion message and exits.

## Updater Utility
The included `updater.exe` handles automatic updates:
- Downloads the latest version of the main executable if available.
- Safely replaces the old executable with the new one.
- Can be run directly or is triggered automatically by the main script when an update is detected.

## Supported Countries for Job Searching

### **LinkedIn**

LinkedIn searches globally. 

### **ZipRecruiter**

ZipRecruiter searches for jobs in **US/Canada**.

### **Indeed**

Indeed supports most countries, you can specify the following countries when searching on Indeed (use the exact name):

|                      |              |            |                |
|----------------------|--------------|------------|----------------|
| Argentina            | Australia    | Austria    | Bahrain        |
| Belgium              | Brazil       | Canada     | Chile          |
| China                | Colombia     | Costa Rica | Czech Republic |
| Denmark              | Ecuador      | Egypt      | Finland        |
| France               | Germany      | Greece     | Hong Kong      |
| Hungary              | India        | Indonesia  | Ireland        |
| Israel               | Italy        | Japan      | Kuwait         |
| Luxembourg           | Malaysia     | Mexico     | Morocco        |
| Netherlands          | New Zealand  | Nigeria    | Norway         |
| Oman                 | Pakistan     | Panama     | Peru           |
| Philippines          | Poland       | Portugal   | Qatar          |
| Romania              | Saudi Arabia | Singapore  | South Africa   |
| South Korea          | Spain        | Sweden     | Switzerland    |
| Taiwan               | Thailand     | Turkey     | Ukraine        |
| United Arab Emirates | UK           | USA        | Uruguay        |
| Venezuela            | Vietnam      |            |                |

### **Bayt**

Bayt only uses the search term currently and searches internationally

## Notes
* Indeed is the best scraper currently with no rate limiting.  
* All the job board endpoints are capped at around 1000 jobs on a given search.  

## Contributing
Contributions are welcome! If you have suggestions for improvements or encounter any issues, please open an issue or submit a pull request.

---
## Disclaimer
**Disclaimer:** This tool is intended for educational and research purposes only. The author does not encourage or endorse misuse. By using this tool, you accept full responsibility for your actions and compliance with job board terms of service and applicable laws. The author is not liable for any consequences, including account bans or legal issues. Use at your own risk.
