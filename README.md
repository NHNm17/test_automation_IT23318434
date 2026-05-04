# Test Automation Assignment - IT23318434

Student Registration Number: IT23318434

## Objective
The objective of this assignment is to test the transliteration accuracy of the Chat Sinhala transliteration function at [https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator).

## Project Structure
- `IT23318434_test_automation.py`: The Playwright automation script.
- `test_automation/`: Folder containing the test case data.
  - `IT23318434_Assignment 1 - Test cases.xlsx`: The completed test cases with results.
- `README.md`: Instructions for setup and execution.
- `Git_Repo_Link.txt`: Link to the public GitHub repository.

## Installation Instructions
1. Install Python 3.11 or later.
2. Clone the repository or extract the zip.
3. Install dependencies:
   ```bash
   py -m pip install playwright openpyxl
   py -m playwright install chromium
   ```

## Execution Instructions
To run the automation script:
```bash
py IT23318434_test_automation.py --excel "test_automation/IT23318434_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
```

## Results
The results are automatically recorded in the `test_automation/IT23318434_Assignment 1 - Test cases.xlsx` file under the 'Actual output' and 'Status' columns.
