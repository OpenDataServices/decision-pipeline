(decision_ticket)=
Decision ticket
===============

Each planned or ongoing decision should be represented by a Plan.io ticket. The usage of the ticket’s fields and custom fields are outlined in the table below. Where usage varies depending on the stage in the decision pipeline, a detailed description is provided in the Decision Pipeline documentation and this is noted in the table.

All fields listed below are REQUIRED unless stated otherwise.

```{list-table} Fields in a decision ticket
:header-rows: 1
:widths: 1 3
* - Field
  - Description
* - Subject
  - A short and up-to-date representation of the decision. <br><br>The issue subject should always begin with a verb, e.g. 'Increase our pay to X', 'Replace Xero with Y'.
* - Status
  - A description of where the decision is in the decision pipeline, chosen from available {ref}`decision statuses<decision_statuses>`.
* - Parent Ticket
  - Main ticket ID where the work to advance the decision is happening.
* - Description
  - A brief {ref}`decision summary<decision_summary>`, or link to an equivalent summary, at a level of detail appropriate to its impact, complexity and stage in the pipeline.
* - Assignee
  - The individual or group being notified of the latest update.
* - Due Date
  - The estimated date that a decision is expected to begin.<br><br>Estimates are expected to be less accurate for decisions earlier in the pipeline.
* - Decision Sponsor
  - The individual responsible for the {ref}`decision sponsor<as_a_decision_sponsor>` role. <br><br>A decision-sponsor is optional while a decision has the {ref}`emerging<emerging>` status but progressing a decision REQUIRES the appointment of a decision sponsor.
* - Decision Team
  - All members of the {ref}`decision team<as_a_decision_team_member>`.
* - Decision Type
  - The type of {ref}`decision-making process<decision_making_processes>` that is planned.
* - Event (optional)
  - The event where the decision is planned to take place, e.g. June 2022 OGM.
```











