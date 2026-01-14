# SlimDesk for Frappe v16

**A streamlined, persistent sidebar navigation for Frappe & ERPNext.**

## The Problem
In the standard Frappe Desk, navigating between different modules (e.g., *Buying* to *Selling*) often requires the user to click "Home" or the Desk icon, returning to the main grid view. This context switch causes users to lose track of their current task and breaks the flow of work.

## The Solution
**SlimDesk** injects a permanent, unobtrusive sidebar on the left side of every application page. It mirrors the standard Desk icons but keeps them accessible at all times.

### Key Features
-   **Persistent Navigation:** Switch modules with 1 click from anywhere.
-   **Context Retention:** No need to return to the "Desktop" grid.
-   **Smart Icons:** 
    -   Professional "Subtle" Grayscale styling by default.
    -   Full color on hover/active.
    -   **Dynamic Fallback:** Automatically detects correct icons for Core ERPNext modules (e.g., Manufacturing, Assignments) and standard FontAwesome icons.
-   **Matches Desk Order:** workspaces are sorted alphabetically to match the standard Desk grid configuration.
-   **Customizable:**
    -   Reorder icons via Drag & Drop.
    -   Add custom links or shortcuts.
    -   Toggle visibility of items.

## Installation

1.  **Get the App**
    ```bash
    bench get-app v16_slim_desk https://github.com/your-org/v16_slim_desk
    ```

2.  **Install on Site**
    ```bash
    bench --site [site-name] install-app v16_slim_desk
    ```

3.  **Update Assets**
    ```bash
    bench build --app v16_slim_desk
    bench clear-cache
    ```

## Usage
Once installed, the sidebar appears automatically for all System Users. 
-   **Customize:** Click the "Edit" (Pencil) icon at the bottom of the sidebar to reorder items or add new shortcuts.
-   **Home:** Click the top "Grid" icon to return to the standard Frappe Desk.

## Compatibility
-   **Frappe Framework:** v15, v16+
-   **ERPNext:** v15, v16+
