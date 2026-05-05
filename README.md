# project_salesforce

Salesforce Validation Rule Manager
A web application that connects with Salesforce using OAuth 2.0 and allows users to:
- View validation rules
- Enable/Disable rules
- Deploy updates back to Salesforce

Tech Stack
- Django
- Salesforce OAuth 2.0
- Salesforce Tooling API
- REST API

Setup Instructions to run locally
- cd crmproject 
- pip install django requests simple-salesforce
- python manage.py makemigrations
- python manage.py migrate

Features
- Salesforce OAuth Login
- Fetch validation rules
- Enable/Disable validation rules
- Deploy updates to Salesforce
- Active/Inactive status display

Screenshots
- <img width="1400" height="900" alt="blood" src="https://github.com/user-attachments/assets/772061e7-db40-4863-a9ec-e433c839f341" />

- Fetch validation rules
- Enable/Disable validation rules
- Deploy updates to Salesforce
- Active/Inactive status display
