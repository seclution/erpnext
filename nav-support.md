# Support Module

Source directory: `erpnext/support`

Main subfolders:

- README.md – brief description of the module
- __init__.py – installs roles like *Support Team* and *Maintenance Manager*
- doctype – DocType folders for:
  - issue
  - issue_priority
  - issue_type
  - pause_sla_on_status
  - service_day
  - service_level_agreement
  - service_level_priority
  - sla_fulfilled_on_status
  - support_search_source
  - support_settings
  - warranty_claim
- page (placeholder)
- report – script reports:
  - first_response_time_for_issues
  - issue_analytics
  - issue_summary
  - support_hour_distribution
- web_form – includes `issues` form
- workspace – contains `support/support.json`
- website route: `erpnext/www/support`

Related modules:
- `erpnext/maintenance` – Warranty Claims can create Maintenance Visits
