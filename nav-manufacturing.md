# Manufacturing Module

Source directory: `erpnext/manufacturing`

Main subfolders:

- README.md
- __init__.py
- dashboard_chart
- dashboard_fixtures.py
- doctype
- manufacturing_dashboard
- module_onboarding
- notification
- number_card
- onboarding
- onboarding_step
- page
- report
- workspace

Key doctypes include `BOM`, `Work Order`, `Job Card`, `Operation`, `Routing`, `Production Plan`, `Workstation`, and `Manufacturing Settings`.

Common pages under `page/`:

- `bom_comparison_tool`
- `visual_plant_floor`

Dashboards and number cards are generated via `dashboard_fixtures.py` and loaded in `manufacturing_dashboard/` and `workspace/`.

Manufacturing workflows rely on the **Stock** module for inventory movements and integrate with **Quality Management** for inspections.
