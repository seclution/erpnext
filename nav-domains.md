# Domains

Configuration related to enabling or restricting industry domains.

## Source directory
- `erpnext/domains` – Python modules that define per-domain setup via a `data` dictionary.
  - `distribution.py`
  - `manufacturing.py`
  - `retail.py`
  - `services.py`

Each file lists desktop icons to show, default values to set and other options when the domain is active.

## Related code
- Workspace JSON files contain `"restrict_to_domain"` to hide pages when a domain is disabled. Examples:
  - `manufacturing/workspace/manufacturing/manufacturing.json`
  - `selling/page/point_of_sale/point_of_sale.json` (domain "Retail")
  - `buying/workspace/buying/buying.json`
- Tests can enable all domains using `enable_all_roles_and_domains` in `erpnext/setup/utils.py`.
- Patches such as `erpnext/patches/v11_1/setup_guardian_role.py` call `frappe.get_active_domains()` to add data only for certain domains.
- The Company doctype (`erpnext/setup/doctype/company/company.json`) includes a "Domain" field used during setup.
