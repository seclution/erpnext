# Subcontracting Module

Source directory: `erpnext/subcontracting`

Main subfolders:

- __init__.py
- doctype

### Doctypes

- subcontracting_bom
- subcontracting_order
- subcontracting_order_item
- subcontracting_order_service_item
- subcontracting_order_supplied_item
- subcontracting_receipt
- subcontracting_receipt_item
- subcontracting_receipt_supplied_item

### Related Code

- `erpnext/controllers/subcontracting_controller.py` – shared business logic for orders and receipts
- `erpnext/controllers/tests/test_subcontracting_controller.py` – controller tests
- `erpnext/patches/v15_0/rename_subcontracting_fields.py`
- `erpnext/patches/v14_0/copy_is_subcontracted_value_to_is_old_subcontracting_flow.py`
- `erpnext/patches/v14_0/change_is_subcontracted_fieldtype.py`

This module integrates with stock and manufacturing workflows to handle outsourced production.
