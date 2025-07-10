# Selling Module

Source directory: `erpnext/selling`

Main subfolders:

- README.md
- __init__.py
- dashboard_chart
- doctype
- form_tour
- module_onboarding
- number_card
- onboarding_step
- page
- print_format
- print_format_field_template
- report
- selling_dashboard
- workspace

Key doctypes (in `erpnext/selling/doctype`):

- `customer` – customer master and dashboard
- `quotation` – quote document and related items
- `sales_order` – sales order and items
- `product_bundle` – bundled products
- `selling_settings` – module configuration
- other supporting doctypes like `customer_credit_limit`, `party_specific_item`, `sms_center`

Important pages (`erpnext/selling/page`):

- `point_of_sale` – Point of Sale interface with JS and Python controllers
- `sales_funnel` – sales funnel dashboard page

Reports (`erpnext/selling/report`): numerous built‑in sales analytics reports such as `sales_order_analysis`, `sales_analytics`, `quotation_trends`, and more.

Dashboards and workspace:

- `dashboard_chart` and `number_card` provide chart and card JSON definitions
- `selling_dashboard/selling` and `workspace/selling` define the selling workspace
- `module_onboarding/selling` and `onboarding_step/*` configure onboarding flow

Related utilities:

- `erpnext/public/js/utils/sales_common.js` – shared client‑side logic
- `erpnext/controllers/selling_controller.py` – base controller used by doctypes
