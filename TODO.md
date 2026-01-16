# SlimDesk Navigator TODO

## Backlog
- [ ] 

## Deferred / Known Issues
- [ ] **Feature: Restore Defaults Button** (v3.42-v3.46)
    - **Status:** Backend API implemented. Frontend Button persistently invisible or causes layout regressions in Production.
    - **Goal:** Allow users to reset sidebar to original state.

## Completed
- [x] **Bug: Icons Unresponsive after System Reload** (v3.41) **Bug: Icons Stop Working after System Reload**
    - **Scenario:** Changing system settings triggers a Frappe "Reload" modal. After this reload, SlimDesk icons become unresponsive or disappear.
    - **Workaround:** Navigating to Desk URL + Hard Refresh restores functionality.
    - **Suspect:** Initialization logic doesn't re-trigger correctly after a soft `frappe.ui.reload` or DOM replacement. 

## Completed
- [x] v3.40 Public Release
