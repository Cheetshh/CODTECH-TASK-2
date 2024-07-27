NAME:DHEERAJ DONIKENA

COMPANY:CODETECH IT SOLUTIONS PVT LTD

ID:CT8CSEH1189

DOAMIN:CYBER SECUIRTY

DURATION:20 JUNE 2023 TO AUG 20 2023

MENTOR:SANTHOSH KUMAR

OVERVIEW OF PROJECT:

### Project Overview

This project is a simple web-based vulnerability scanning tool designed to analyze a network or website for common security issues. It focuses on detecting open ports, outdated software versions, and misconfigurations. The application is built using Python's Flask framework and uses external libraries to perform network scanning and HTTP requests. The tool provides an intuitive web interface where users can input the target IP address and URL to perform scans and view the results.

### Activities

1. **Open Ports Scanning**: 
   - The tool scans a specified range of ports (1-1024) on a given IP address to identify which ports are open. This helps in determining which network services are exposed and potentially vulnerable.

2. **Software Version Checking**:
   - The application checks the server response headers of a specified URL to identify the software and its version running on the server. It compares this information against known vulnerable versions to highlight potential security risks.

3. **Misconfiguration Detection**:
   - The tool performs a basic check of the HTTP response from a target URL to identify misconfigurations, such as unexpected HTTP status codes. This helps in identifying issues like misconfigured web servers or services.

### Technologies Used

1. **Python**:
   - Python is the primary programming language used for developing the backend logic of the application. It handles the core functionality, such as network scanning, HTTP requests, and processing results.

2. **Flask**:
   - Flask is a lightweight web framework for Python. It is used to create the web application, define routes, and render HTML templates. Flask provides the necessary tools to build and deploy the web interface.

3. **nmap**:
   - `nmap` is a network scanning tool used to discover open ports and services running on a target IP address. The `python-nmap` library provides a Python interface to interact with `nmap`.

4. **requests**:
   - The `requests` library is used to make HTTP requests to the target URL. It retrieves response headers and status codes to check for vulnerable software versions and misconfigurations.

5. **HTML/CSS**:
   - HTML (HyperText Markup Language) is used to structure the web pages of the application. CSS (Cascading Style Sheets) is used for styling the pages, ensuring a user-friendly and visually appealing interface.

### Explanation

The project is structured to provide a user-friendly web application that performs vulnerability scanning tasks:

1. **User Interface**:
   - Users interact with the application through a web form where they input the target IP address and URL. The form submission triggers the scanning processes.

2. **Backend Logic**:
   - When the form is submitted, the Flask application processes the input, performs the network scan for open ports using `nmap`, checks for software versions using the `requests` library, and detects misconfigurations. 

3. **Result Display**:
   - After completing the scans, the results are compiled and rendered on a results page. The page displays open ports, any detected vulnerable software versions, and any misconfigurations identified during the scan.

4. **Styling and Presentation**:
   - The application uses CSS to enhance the visual presentation of the web pages. It includes a background image and styled elements to improve user experience and make the interface more attractive.

Overall, this project combines various technologies to create a functional and user-friendly vulnerability scanning tool, providing essential security insights through a web-based interface.

