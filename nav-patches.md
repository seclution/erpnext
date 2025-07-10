# Patches & Change Log

Database patches and release notes for upgrades.

- `erpnext/patches/` – patch modules organized by version folders (`v10_0`, `v11_0`, `v12_0`, `v13_0`, `v14_0`, `v15_0`, etc.). Each file exposes an `execute()` function run during migrations.
- `erpnext/patches.txt` – ordered list of patches that have been applied.
- `erpnext/change_log/` – versioned release notes. `current/` holds upcoming notes.
- `.github/workflows/patch.yml` – CI workflow testing patch migrations.
- `erpnext/tests/test_init.py` – includes a patch file validation test.
- `CODEOWNERS` – patch directory owners listed for review responsibility.
