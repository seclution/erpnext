# Projects Module

Source directory: `erpnext/projects`

Main subfolders:

- `__init__.py`
- `dashboard_chart` – chart definitions
- `doctype` – Project DocTypes
- `projects_dashboard` – module dashboard
- `report` – standard reports
- `utils.py`
- `web_form` – web forms
- `workspace` – workspace config

## DocTypes
- Activity Cost
- Activity Type
- Dependent Task
- Project
- Project Template
- Project Template Task
- Project Type
- Project Update
- Project User
- Projects Settings
- Task
- Task Depends On
- Task Type
- Timesheet
- Timesheet Detail

## Reports
- Billing Summary
- Daily Timesheet Summary
- Delayed Tasks Summary
- Employee Billing Summary
- Project Billing Summary
- Project Summary
- Project Wise Stock Tracking

## Web Templates
- `templates/pages/projects.{html,js,py}` – project portal page
- `templates/pages/task_info.{html,py}` – task details
- `templates/pages/timelog_info.{html,py}` – time log view
- `templates/includes/projects/*.html` – project includes

## Other
- `web_form/tasks` – public Tasks form
- `workspace/projects/projects.json` – workspace layout
- `dashboard_chart/project_summary/project_summary.json`
- `projects_dashboard/project/project.json`
