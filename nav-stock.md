# Stock Module

Source directory: `erpnext/stock`

Main subfolders:

- README.md
- __init__.py
- dashboard
- dashboard_chart
- dashboard_chart_source
- deprecated_serial_batch.py
- doctype
- form_tour
- get_item_details.py
- module_onboarding
- number_card
- onboarding_step
- page
- print_format
- reorder_item.py
- report
- serial_batch_bundle.py
- spec
- stock_balance.py
- stock_dashboard
- stock_ledger.py
- tests
- utils.py
- valuation.py
- workspace

Key doctypes and related directories:

- `doctype/item` – item master data
- `doctype/warehouse` – warehouse records
- `doctype/stock_entry` – stock transactions
- `doctype/batch` and `doctype/serial_no` – batch and serial number tracking
- `doctype/stock_ledger_entry` – ledger of all stock movements
- `doctype/stock_reconciliation` – adjustments of stock quantities
- documents like `delivery_note`, `purchase_receipt`, and `material_request`
  include stock-related child tables

Utility modules and controllers:

- `controllers/stock_controller.py` – shared logic for stock documents
- `stock/get_item_details.py` – helper to pull item data
- `stock/stock_ledger.py` – create and update ledger entries
- `stock/stock_balance.py` – queries for current stock quantities
- `stock/reorder_item.py` – automation for reorder levels
- `stock/valuation.py` – FIFO/LIFO valuation methods
- `stock/utils.py` – general stock helpers

Reports and dashboards:

- various reports under `stock/report` such as `stock_ledger` and
  `stock_balance`
- dashboard charts under `stock/dashboard_chart`
- workspace setup in `stock/workspace`

Reference specifications:

- `stock/spec/README.md` and `stock/spec/reposting.md`

