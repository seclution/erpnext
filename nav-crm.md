# CRM Module

Source directory: `erpnext/crm`

Main subfolders and files:

- `__init__.py`
- `crm_dashboard/` – dashboard config JSON
- `dashboard_chart/` – charts like `incoming_leads` and `opportunity_trends`
- `doctype/` – CRM doctypes (Lead, Opportunity, Prospect, Campaign, Contract, etc.)
- `frappe_crm_api.py` – integration helpers for Frappe CRM
- `module_onboarding/` – module level onboarding
- `number_card/` – number card definitions
- `onboarding/` – onboarding configuration
- `onboarding_step/` – JSON steps used in onboarding
- `report/` – built‑in CRM reports
- `utils.py` – utilities (link communications, CRMNotes, open activities)
- `workspace/` – workspace layout

Related files elsewhere in the repository:

- `erpnext/public/js/utils/crm_activities.js` – front‑end widget for open tasks & events
- `erpnext/public/js/templates/crm_activities.html` and `crm_notes.html`
- `erpnext/public/js/communication.js` – actions to create leads or opportunities from communications
- `erpnext/telephony/doctype/call_log/call_log.py` – links call logs with leads
- `erpnext/hooks.py` – registers CRM event hooks and scheduler tasks
- `erpnext/patches/*` – migration scripts touching CRM doctypes
- other modules like `buying` and `selling` import CRM utilities when creating quotations or RFQs
