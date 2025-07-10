# Quality Management Module

Source directory: `erpnext/quality_management`

Main subfolders:

- __init__.py
- doctype
- report
- workspace

### DocTypes

- non_conformance
- quality_action
- quality_action_resolution
- quality_feedback
- quality_feedback_parameter
- quality_feedback_template
- quality_feedback_template_parameter
- quality_goal
- quality_goal_objective
- quality_meeting
- quality_meeting_agenda
- quality_meeting_minutes
- quality_procedure
- quality_procedure_process
- quality_review
- quality_review_objective

### Other folders

- `report/review`
- `workspace/quality`

### Related Modules

- Stock module contains quality inspection DocTypes under `erpnext/stock/doctype`.
- Manufacturing module includes reports like `quality_inspection_summary`.

### Tests

- `erpnext/quality_management/doctype/**/test_*.py`

