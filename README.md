# LinkedIn Job Application Automation

This Python script automates the process of applying for jobs on LinkedIn using Selenium. The script logs into LinkedIn, navigates to a specific job posting, and applies for the job.

## Prerequisites

Before running the script, make sure you have the following installed:

- [Python 3.x](https://www.python.org/downloads/)
- [Selenium](https://pypi.org/project/selenium/)
- [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) (Ensure the version matches your Chrome browser version)

## Installation

1. Clone the repository or download the script to your local machine.

2. Install the required Python packages:

    ```bash
    pip install selenium
    ```

3. Download and install [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads). Ensure the `chromedriver.exe` is placed in a known directory (e.g., `C:\Development\chromedriver.exe`).

## Usage

1. **Update the script:**
   
   Replace the placeholders in the script with your LinkedIn credentials:

   ```python
   username.send_keys("your-email@example.com")
   password.send_keys("your-password")
