# Maintenance Module

Source directories:

- `erpnext/maintenance` – core maintenance module
- `erpnext/assets/doctype` – asset maintenance doctypes

Main subfolders under `erpnext/maintenance`:

- `__init__.py`
- `doctype/`
  - `maintenance_schedule/`
  - `maintenance_schedule_detail/`
  - `maintenance_schedule_item/`
  - `maintenance_visit/`
  - `maintenance_visit_purpose/`
- `report/`
  - `maintenance_schedules/`

Related asset maintenance folders:

- `erpnext/assets/doctype/asset_maintenance/`
- `erpnext/assets/doctype/asset_maintenance_log/`
- `erpnext/assets/doctype/asset_maintenance_task/`
- `erpnext/assets/doctype/asset_maintenance_team/`
- `erpnext/assets/doctype/maintenance_team_member/`
- `erpnext/assets/report/asset_maintenance/`

Maintenance patches:

- `erpnext/patches/v13_0/set_status_in_maintenance_schedule_table.py`
- `erpnext/patches/v13_0/update_maintenance_schedule_field_in_visit.py`
- `erpnext/patches/v15_0/update_task_assignee_email_field_in_asset_maintenance_log.py`
