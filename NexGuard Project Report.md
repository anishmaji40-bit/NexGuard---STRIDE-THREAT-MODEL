# NexGuard Website Project Report

## 1. Project overview

NexGuard is a browser-based cybersecurity threat-modeling demonstration. It helps a visitor sketch an application, consider common STRIDE threats, estimate risk, and track possible mitigations. The site currently works without registration or sign-in.

## 2. Public website

### Main navigation

The top navigation links visitors to the platform overview, use cases, STRIDE methodology, the resource library, data-handling information, and contact page. The account link explains that registration and cloud sync are in progress. The main call to action opens the demo workspace directly.

### Home page

- **Hero and product preview:** Introduces NexGuard and shows an illustrative architecture diagram with example findings. Visitors can open the demo or explore platform details.
- **Workflow overview:** Explains four stages: map the system, review STRIDE threats, assess risk, and track mitigations.
- **Interactive STRIDE explorer:** Lets visitors select one of six threat categories and read a scenario, discussion question, and example prompt.
- **Review workflow:** Shows how a team can move from architecture mapping through threat review, risk discussion, and mitigation.
- **Use-case showcase:** Describes how developers, security engineers, architects, DevSecOps teams, and enterprise teams can use a shared model.
- **Risk scoring tool:** Allows visitors to change likelihood and impact values and see the illustrative score and severity update.
- **Getting-started and template sections:** Show how to start with a familiar architecture and add details as the review develops.
- **FAQ and final call to action:** Answers common questions about threat modeling, STRIDE, reports, and demo limitations, then invites visitors to open the workspace.
- **Footer:** Provides links to the platform, use cases, STRIDE guide, resources, data handling, contact, and demo.

### Platform overview

Summarizes the main capabilities: architecture diagrams, STRIDE prompts, threat records, risk scoring, mitigation tracking, and JSON or CSV exports. Collaboration and integrations are identified as planned or not connected.

### Use cases

Explains how different roles can use the workflow. Developers capture implementation-level risks; security engineers review threats; architects discuss trust boundaries; DevSecOps teams track remediation; enterprise teams can use the common review structure as a starting point.

### STRIDE methodology

Introduces Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, and Elevation of Privilege. It recommends defining scope, mapping components and data flows, validating threat scenarios, and documenting risk decisions and mitigations.

### Resource library

Collects introductory guides and examples for threat-modeling reviews. Visitors can search the resource cards and follow links to methodology or example content.

### Data handling and security

Explains that the current demo stores workspace edits only in the current browser. It does not use a login server, cloud database, or cross-device sync. It also describes planned account, team, and production capabilities.

### Contact

Presents enterprise discussion topics and a contact form. The form validates entries in the browser, but no email or CRM service is connected, so it does not send a message.

### Plans and billing information

The plan page is a placeholder for future pricing and plan comparisons. No prices, payment processing, subscriptions, or usage limits are configured.

### Account features in progress

Visitors do not need to create an account to use the demo. Email registration, sign-in, cloud backup, cross-device synchronization, and team workspaces are explicitly shown as in progress.

## 3. Demo workspace

The workspace uses a sidebar to move between the following areas:

### Overview

Shows the current workspace, project and model totals, open threats, high or critical findings, mitigation counts, recent projects, and recent activity. It links directly to model creation and other workspace pages.

### Projects

Lists projects and provides search, sorting, project creation, project details, and project actions. Each project can contain one or more threat models.

### Templates

Shows illustrative architecture templates. A visitor can preview and duplicate a template to create an editable starting model.

### Create Model

Offers three starting options: build from a blank canvas, use a template, or describe a system and define its scope.

### Architecture

Provides the editable model canvas. Visitors can add and move components, describe their type and data classification, connect components with data flows, and review model details. The sample trust boundary is illustrative.

### Threat Analysis

Displays the threat register, severity summaries, search and filters, risk scores, and threat details. Visitors can add or update findings and download a CSV. Demo analysis uses deterministic prompts; it is not AI-generated or a verified assessment.

### Mitigations

Shows proposed controls connected to threats. Visitors can review owners and change mitigation status as work progresses.

### Reports

Previews a threat-model summary and supports JSON and CSV downloads. PDF export is not available.

### Team Activity

Shows a local activity feed of changes made in the current browser workspace.

### Notifications

A placeholder because no notification service is connected.

### Integrations

A placeholder because external services have not been configured.

### Members

A placeholder for invitations, user roles, and team authorization, which are still in progress.

### Usage and Billing

Shows plan and billing information as unconfigured. No purchases or subscription controls are active.

### Audit Logs

Explains that the demo has a local activity feed but no tamper-resistant, server-side audit log.

### Settings

Allows editing the demo display name and workspace name. These are local browser preferences; the page also identifies sign-in, cloud backup, and team workspace features as in progress.

## 4. Data and operating notes

Workspace changes are saved in the browser's local storage. They remain on that browser profile and device; they are not shared, backed up, or automatically recoverable. Clearing browser data can remove them. Visitors should use sample or non-sensitive information.

The website can be opened as a static site and does not require the former Python server. Existing legacy account data is kept separate from the current demo and must not be published with the website.

## 5. Current limitations

NexGuard is a demonstration rather than a production security service. Threat prompts and risk scores require human review. Login, email verification, password recovery, cloud persistence, team collaboration, integrations, billing, notifications, and server-side audit logging are not active. Contact submissions are not delivered.
