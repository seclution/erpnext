# Regional Module

Source directory: `erpnext/regional`

Main subfolders:

- `__init__.py`
- `address_template/` – region-specific address formats
  - `README.md`
  - `setup.py`
  - `templates/` (e.g. `germany.html`, `luxembourg.html`)
  - `test_regional_address_template.py`
- `doctype/`
  - `import_supplier_invoice/`
  - `lower_deduction_certificate/`
  - `south_africa_vat_settings/`
  - `uae_vat_account/`
  - `uae_vat_settings/`
- `italy/` – `setup.py`, `utils.py`, `e-invoice.xml`
- `print_format/`
  - `detailed_tax_invoice/`
  - `irs_1099_form/`
  - `purchase_einvoice/`
  - `simplified_tax_invoice/`
  - `tax_invoice/`
- `report/`
  - `electronic_invoice_register/`
  - `irs_1099/`
  - `uae_vat_201/`
  - `vat_audit_report/`
- `south_africa/` – `setup.py`
- `turkey/` – `setup.py`
- `united_arab_emirates/` – `setup.py`, `utils.py`
- `united_states/` – `setup.py`, `test_united_states.py`

Related patches invoking these modules are located in `erpnext/patches`.

