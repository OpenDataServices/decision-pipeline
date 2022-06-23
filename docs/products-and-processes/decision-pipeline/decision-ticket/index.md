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
* - Decision Link
  - A link to the ticket or poll where the decision is taking place.
* - Description
  - Emerging decisions or simple decisions at any stage of the pipeline may provide a {ref}`decision summary<decision_summary>` in the description field.<br><br>Complex decisions must provide a decision summary in a separate document using the `Decision Summary` field.
* - Decision Summary
  - A link to a document containing a {ref}`decision summary<decision_summary>`.<br><br>This field is optional for emerging decisions or simple decisions at any stage of the pipeline.
* - Assignee
  - The individual or group being notified of the latest update.
* - Due Date
  - The estimated date that a decision is expected to begin.<br><br>Estimates are expected to be less accurate for decisions earlier in the pipeline.
* - Decision Start Date
  - The date that a decision is scheduled to begin. (Scheduled decisions only.)
* - Decision End Date
  - The date that a decision is scheduled to end. (Scheduled decisions only.)
* - Decision Facilitator
  - The individual responsible for the {ref}`decision facilitator<as_a_decision_facilitator>` role. <br><br>A decision-facilitator is optional while a decision has the {ref}`emerging<emerging>` status but progressing a decision REQUIRES the appointment of a decision facilitator.
* - Decision Team
  - All members of the {ref}`decision team<as_a_decision_team_member>`.
* - Decision Type
  - The type of {ref}`decision-making process<decision_making_processes>` that is planned.
* - Event (optional)
  - The event where the decision is planned to take place, e.g. June 2022 OGM.
* - Team Coordination Ticket
  - The ticket where the work of progressing the ticket is happening. <br><br>Optional if this is the same as the parent ticket.
 * - External Communication Ticket
   - The ticket where any communication with people outside the decision team is happening <br><br>Optional if this is the same as the parent ticket.
```











