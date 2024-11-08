This project is designed strictly for educational and authorized penetration testing purposes. Unauthorized phishing attempts are illegal and unethical. Ensure you have explicit permission to deploy this project in any environment outside of a controlled lab setup.

This project provides a sophisticated phishing simulation that demonstrates a fundamental understanding of web-based credential harvesting techniques. It involves the construction of a simulated Snapchat login interface, customized scripting using PHP, and secure handling of captured data within a local server environment. The project integrates HTML, PHP, and server configuration, providing a deeper understanding of both the creation and detection of phishing attacks, which is vital for cybersecurity training.

Prerequisites
To implement this simulation, you’ll need a Debian-based Linux environment with Apache web server installed, along with a working knowledge of HTML and PHP scripting. Familiarity with web server configuration is also highly recommended, as this setup involves custom modifications within Apache’s root directory.

Project Structure
In the Apache root directory (/var/www/html/snapchat-phish/), the project consists of the following files:

index.html: This file simulates the login page of Snapchat with custom HTML and embedded JavaScript, mimicking the look and feel of the official login interface.
capture.php: A PHP script engineered to securely intercept, process, and store the provided credentials locally in a file, credentials.txt.
credentials.txt: A local text file where captured credentials are saved, allowing for secure data collection in this controlled environment.
