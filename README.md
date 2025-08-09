# Phishing-Simulation-Awareness-Automation
This project implements an end-to-end phishing simulation and awareness automation system. It enables security teams to conduct realistic phishing campaigns using dynamic email templates and custom landing pages, safely capturing user interactions for analysis.

The platform tracks user responses securely, logs interactions into a lightweight database, and provides interactive dashboards to visualize campaign effectiveness and user behavior. Additionally, automated feedback and training workflows educate users to improve phishing resilience.

# Features

- Automated phishing email campaign generation with customizable templates
- Custom landing pages mimicking real-world phishing attacks to safely capture user interactions
- Secure tracking and logging of user responses using SQLite database
- Interactive analytics dashboards for real-time visualization of campaign results
- Automated workflows to provide user feedback and targeted security awareness training
- Modular design for easy expansion and integration with existing security infrastructure

# Technology Stack
- Backend: Python, Flask
- Email Delivery: SMTP protocol
- Database: SQLite
- Frontend: HTML, CSS (for landing pages and dashboards)
- Other Tools: Jinja2 (templating), logging libraries, etc.

# Getting Started

### Prerequisites
- Python 3.x
- SMTP server acess (e.g., Gmail SMTP, local SMTP server)
- Basic knowleedge of Python and Flask

### Installation
``
git clone...
cd ...
pip install ...
WILL FINISH THIS SECTION LATER
``
### Configuration
- Update SMTP server credentials in config.py
- Customize email templates and landing pages in the /template folder
- Initialize or migrate the SQLite database with python init_db.py

### Running the Application
`` python app.py ``

# Usage
- Launch the platform and configure phishing campaigns
- Monitor campaign progress and user interaction via dashboards
- Use automated workflows to send training materials based on user behavior
