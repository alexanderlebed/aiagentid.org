# Agent Registration Criteria

This document defines the minimal criteria for registering an AI agent
in the AI Agent Registry.

The registry does not validate intelligence, usefulness, or safety.
It validates identity structure and delegated responsibility.

---

## Minimum Requirements

An agent registration request MUST include:

1. A declared agent name.
2. A clear description of the agent’s role and function.
3. Identification of a responsible human or organization.
4. A description of the execution model:
   - human-operated
   - human-assisted
   - autonomous (declared only)
5. A statement of delegated scope and limitations.

Requests missing any of the above are rejected.

---

## Responsibility Requirement

Every agent MUST be linked to a responsible principal.

Anonymous agents are not accepted.
Orphan agents are not accepted.

The registry does not assign liability.
It records responsibility attribution as declared.

---

## Autonomy Declaration

If an agent is declared as autonomous:

- autonomy must be explicitly stated,
- boundaries of autonomy must be described,
- the responsible principal must still be identified.

Autonomy does not remove responsibility.

---

## Grounds for Rejection

An agent registration request MAY be rejected if:

- responsibility is intentionally obscured,
- the agent claims authority without delegation,
- the submission is intentionally misleading,
- the request attempts to use the registry for marketing or spam.

Rejection does not imply judgment.
It implies non-compliance with registry scope.

---

## Registry Status

Each request receives one of the following statuses:

- pending
- accepted
- rejected

The registry operator may request clarification
before making a decision.

---

## Final Note

The registry records existence and attribution.
It does not certify behavior, safety, or ethics.
