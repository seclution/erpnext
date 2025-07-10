# Setup Module

Source directory: `erpnext/setup`

Main contents:

- `__init__.py`
- `default_energy_point_rules.py` – built‑in energy point configuration.
- `default_success_action.py` – helper for generic success messages.
- `demo.py` – scripts to create or clear sample data.
- `demo_data/` – JSON fixtures used by `demo.py`.
- `doctype/` – configuration DocTypes (Company, Department, Item Group, etc.).
- `form_tour/` – interactive tours for onboarding forms.
- `install.py` – post‑install hooks and default setup.
- `module_onboarding/` – workspace data for module onboarding.
- `onboarding_step/` – step definitions for guided setup.
- `page/` – location for setup‑related pages.
- `setup_wizard/` – initial setup wizard with data and operations.
- `utils.py` – helper utilities for tests and defaults.
- `workspace/` – workspace JSON files like Home and ERPNext Settings.

Additional references:

- `erpnext/public/js/utils/demo.js` – toolbar action to clear demo data.

