# EDI Module

Source directory: `erpnext/edi`

Main subfolders:

- `__init__.py`
- `doctype`
  - `code_list`
    - `code_list.json` – doctype schema
    - `code_list.py` – server logic
    - `code_list.js` – form script
    - `code_list_list.js` – list view settings
    - `code_list_import.py` – genericode import helpers
    - `code_list_import.js` – import dialog
    - `test_code_list.py`
  - `common_code`
    - `common_code.json`
    - `common_code.py`
    - `common_code.js`
    - `common_code_list.js`
    - `test_common_code.py`

Related entries:

- `hooks.py` registers `doctype_list_js` for the importer UI.

