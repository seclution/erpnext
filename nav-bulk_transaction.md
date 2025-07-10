# Bulk Transaction Module

Source directory: `erpnext/bulk_transaction`

Main subfolders:

- __init__.py
- doctype

### Doctypes

- `bulk_transaction_log` - summary log for a specific date
- `bulk_transaction_log_detail` - records each created document

### Related Files

- `erpnext/utilities/bulk_transaction.py` - server side processing and retry logic
- `erpnext/public/js/bulk_transaction_processing.js` - helper used by list views
- `erpnext/hooks.py` - schedules periodic `bulk_transaction.retry`

List view scripts across `buying`, `selling`, `accounts` and `stock` use the
`bulk_transaction_processing.create` helper to generate related documents in
bulk from selected rows.

