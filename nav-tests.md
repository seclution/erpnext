# Tests

Automated test suites for ERPNext. Python tests typically
inherit from `frappe.tests.utils.FrappeTestCase` or `unittest.TestCase`.

- `erpnext/tests` – high level tests and shared utilities.
- `erpnext/tests/utils.py` – helpers for creating common test data.
- `erpnext/controllers/tests` – tests for controller logic.
- `erpnext/stock/tests` – tests for the Stock module.
- `erpnext/accounts/test` – accounts test helpers and report cases.
- Many doctypes and reports include `test_<name>.py` files directly in their
  folders under `erpnext/**/doctype/**` and `erpnext/**/report/**`.
- A few JavaScript tests use QUnit (e.g.
  `erpnext/manufacturing/doctype/workstation/_test_workstation.js`).
