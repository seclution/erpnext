# Telephony Module

Source directory: `erpnext/telephony`

Main subfolders:

- `__init__.py`
- `doctype`

Key doctypes:

- `call_log`
- `incoming_call_settings`
- `incoming_call_handling_schedule`
- `telephony_call_type`
- `voice_call_settings`

Related assets and hooks:

- `erpnext/public/js/telephony.js` – extends phone fields with a call button
- `erpnext/public/js/call_popup/call_popup.js` – UI for incoming call popups
- `erpnext/public/js/templates/call_link.html` – timeline card for call logs
- `erpnext/public/scss/call_popup.scss` – styles for the call popup
- `erpnext/hooks.py` – connects call logs with contacts and timeline events

