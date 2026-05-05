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
