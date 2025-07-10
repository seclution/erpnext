# Translations

ERPNext uses Frappe's i18n system. Translation strings are stored in CSV files and loaded via hooks.

- `erpnext/translations` – CSV files for each locale.
- `erpnext/hooks.py` – defines `get_translated_dict` for country info.
- `erpnext/tests/test_init.py` – `test_translation_files` validates CSV data.
- `erpnext/setup/utils.py` – setup wizard supplies a default `language`.
- DocType JSONs such as `selling/doctype/customer/customer.json` and
  `stock/doctype/purchase_receipt/purchase_receipt.json` include `language` or
  `Print Language` fields.
- Many print formats set `default_print_language`.
- Templates like `templates/print_formats/includes/item_table_description.html`
  call `doc.get_formatted(..., translated=True)`.
