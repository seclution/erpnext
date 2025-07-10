# Portal Module

Source directory: `erpnext/portal`

Main subfolders:

- __init__.py
- doctype
- utils.py

Portal doctypes:

- homepage
- homepage_section
- homepage_section_card
- website_attribute
- website_filter_field

Portal-related features elsewhere in the codebase:

- `erpnext/utilities/doctype/portal_user` – links system users with Customers/Suppliers
- `erpnext/controllers/website_list_for_contact.py` – manages portal user roles
- `erpnext/selling/doctype/customer` – handles Customer portal user records
- `erpnext/buying/doctype/supplier` – handles Supplier portal user records and migration patches
- `erpnext/support/doctype/issue` – fields and logic for issues created via the portal

