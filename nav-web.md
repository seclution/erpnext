# Web & Templates

Website assets, templates, and portal code.

## Assets

- `erpnext/public/images` – icons and illustrations used on the website and desk.
- `erpnext/public/js` – client-side JavaScript modules.
- `erpnext/public/js/templates` – HTML snippets rendered by JS.
- `erpnext/public/scss` – SCSS stylesheets for website and POS.
- `erpnext/public/sounds` – notification sounds.

## Templates

- `erpnext/templates` – Jinja templates and utility functions.
- `erpnext/templates/emails` – email templates.
- `erpnext/templates/includes` – partial HTML snippets.
- `erpnext/templates/pages` – standard website pages.
- `erpnext/templates/generators` – templates for DocTypes that generate pages.
- `erpnext/templates/form_grid` – grid component templates.
- `erpnext/templates/print_formats` – default print formats.
- `erpnext/templates/utils.py` – helper utilities for templates.

## Website Routes

- `erpnext/www` – Python modules and HTML files mapped to website URLs.
- Specific routes like `www/support` and `www/all-products` live here.
- Additional route rules are configured in `erpnext/hooks.py`.

## Web Forms

- `erpnext/support/web_form` – public Issue form.
- `erpnext/projects/web_form` – Tasks form for project portal.
- `erpnext/utilities/web_form` – Addresses form and others.

## Portal & Shopping Cart

- `erpnext/portal` – portal homepages and related DocTypes.
- `erpnext/controllers/website_list_for_contact.py` – manages portal lists and permissions.
- `erpnext/shopping_cart` – shopping cart portal templates and `web_template` folder.
