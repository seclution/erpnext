# ERPNext Integrations Module

Source directory: `erpnext/erpnext_integrations`

Main subfolders:

- __init__.py
- custom
  - contact.json
- doctype
  - plaid_settings/
    - plaid_settings.py
    - plaid_settings.js
    - plaid_settings.json
    - plaid_connector.py
    - test_plaid_settings.py
- utils.py
- workspace
  - erpnext_integrations/erpnext_integrations.json

Integration-related patches under `erpnext/patches`:

- v12_0/move_plaid_settings_to_doctype.py
- v13_0/shopify_deprecation_warning.py
- v15_0/remove_exotel_integration.py
- v15_0/delete_payment_gateway_doctypes.py
- v15_0/delete_taxjar_doctypes.py
- v15_0/delete_woocommerce_settings_doctype.py

Other references:

- `accounts/doctype/bank/bank.js` – calls Plaid APIs.
- `public/js/help_links.js` – links for PayPal, Razorpay, Dropbox, LDAP, Stripe.

