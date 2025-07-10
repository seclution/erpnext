# Communication Module

Source directory: `erpnext/communication`

The module defines communication mediums and their time slots for assigning
employees to handle incoming requests.

Main contents:

- `__init__.py`
- `doctype/`
  - `communication_medium/`
  - `communication_medium_timeslot/`

Related files:

- `erpnext/public/js/communication.js` – custom form script for the Frappe
  **Communication** DocType (registered via `erpnext/hooks.py`).
- `erpnext/crm/doctype/utils.py` – helper `get_scheduled_employees_for_popup()`
  queries `Communication Medium Timeslot` to find available employees.
- `erpnext/templates/pages/task_info.py` – uses the **Communication** DocType to
  display comments for a task.

