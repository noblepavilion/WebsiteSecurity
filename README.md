# security_tool4
This Python script, named security_tool4, serves as an automated security tool designed for website security assessments. The tool incorporates various checks, including SSL/TLS verification, security headers analysis, and a basic SQL injection scan.

# Usage
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/security_tool4.git
cd security_tool4
Install Dependencies

bash
Copy code
pip install requests beautifulsoup4
Run the Tool

bash
Copy code
python security_tool4.py
Enter the website URL when prompted.

# Functionality
1. IP Address Retrieval
Retrieves the IP address of the specified website.
2. SSL/TLS Checks
Verifies the SSL/TLS status of the website.
Provides information on security or potential vulnerabilities.
3. Security Headers Analysis
Analyzes and displays the security headers of the website.
4. SQL Injection Scan
Scans for potential SQL injection vulnerabilities.
Provides notifications if a vulnerability is found.
# Error Handling
The tool handles errors gracefully and provides informative messages in case of issues.
Notes
# This tool utilizes the socket, requests, and BeautifulSoup libraries.
# Ensure you have Python installed on your system.
For SSL/TLS checks, potential false negatives may occur based on server configurations.

# Contribution
Feel free to contribute by opening issues, suggesting improvements, or adding new features. Pull requests are welcome!




