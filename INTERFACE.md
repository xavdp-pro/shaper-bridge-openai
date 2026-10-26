# Interface responsibilities

A compatible adapter declares inference, tools/acting, prepared context, history
inspection, portable replay, native resume, branch creation, workspace binding,
attachments, streaming, cancellation and persistence independently. Capability
negotiation precedes invocation; a shared protocol does not make engines equal.

The session service supports prepare, inspect, invoke, inspect outcome and branch.
A mission carries `task_id` or another stable request identity, `conversation`,
`context`, `mandate`, `permissions`, `jurisdiction`, engine/model selection and
precise input. A result carries the matching invocation, state and outcome.

Maestro schedules identified work. Queue preserves its delivery identity. A worker
calls the selected cognition adapter within the mission's rights and jurisdiction.
A provider receipt is not Queue acceptance; a pending attempt is not completion.
The tandem retains the decision to continue, adjust or conclude.
