# NexGuard

NexGuard is a static threat-modeling demo. Visitors can explore the workspace without creating an account. Email sign-in, cloud-saved workspaces, and team accounts are marked as in progress.

## Open the demo

Open index.html in a browser, or publish the contents of this folder to a static web host. No Python server, database, or package installation is required for the demo.

## Before publishing

The old login version may have left a data folder containing account records. This demo does not use it. Do not upload or publish the data folder. If an old NexGuard server is still running in PowerShell, stop it with Ctrl+C; this version no longer needs it.

## Demo data

- Sample projects, models, and findings load in the browser.
- Changes are saved in that browser's local storage.
- Data does not sync between browsers or devices and is not backed up.
- Clearing browser storage can permanently remove demo changes.
- Reset workspace data from the app to clear its saved demo workspace.
- Registration, sign-in, password recovery, cloud persistence, and collaboration are in progress.

## Demonstration limits

Threat suggestions use deterministic demo rules; no AI service is called. Sample findings and risk scores are illustrative and are not a verified security assessment or certification. JSON and CSV report downloads are available; PDF export is not implemented.
