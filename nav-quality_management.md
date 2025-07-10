# Quality Management Module

Source directory: `erpnext/quality_management`

Main subfolders:

- __init__.py – module init (empty)
- doctype – individual DocType folders for the module
  - `non_conformance`
  - `quality_action` and `quality_action_resolution`
  - `quality_feedback` with related templates and parameters
  - `quality_goal` and `quality_goal_objective`
  - `quality_meeting` along with agenda and minutes
  - `quality_procedure` and `quality_procedure_process`
  - `quality_review` and `quality_review_objective`
- report – contains the *Review* query report
- workspace – workspace definition in `quality/quality.json`

Other related references appear in the manufacturing module (e.g. Quality Inspection)
and patches setting up quality records.

