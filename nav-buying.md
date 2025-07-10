# Buying Module

Source directory: `erpnext/buying`

Main subfolders:

- README.md
- __init__.py
- buying_dashboard
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
- utils.py
- workspace

Key DocTypes:

- Purchase Order
- Supplier
- Supplier Quotation
- Request for Quotation
- Supplier Scorecard

Related code outside this module:

- `erpnext/controllers/buying_controller.py` – base class for buying transactions
- `erpnext/controllers/subcontracting_controller.py` – provides subcontracting features used in buying
- `erpnext/controllers/accounts_controller.py` – integrates buying logic into accounting
- `erpnext/stock/doctype/purchase_receipt/` – Purchase Receipt built on BuyingController
- `erpnext/stock/onboarding_step/buying_settings/` – onboarding JSON for buying setup
- `erpnext/patches/v12_0/add_default_buying_selling_terms_in_company.py`
- `erpnext/patches/v11_0/check_buying_selling_in_currency_exchange.py`

