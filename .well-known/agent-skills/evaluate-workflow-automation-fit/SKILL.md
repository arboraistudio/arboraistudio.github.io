---
name: evaluate-workflow-automation-fit
description: Evaluate whether a business workflow is a practical fit for Arbor AI Studio and identify the most relevant public service or next step.
---

# Evaluate Workflow Automation Fit

## When to Use This Skill

Use this skill when a user asks whether Arbor AI Studio can automate a repetitive
business process, connect existing tools, or build a human-reviewed AI workflow.
This is a read-only qualification guide. It does not call an Arbor API, submit a
form, book a meeting, or promise an implementation result.

## Public Sources

- Service overview: https://arboraistudio.com/services/
- Industries: https://arboraistudio.com/industries/
- Pricing: https://arboraistudio.com/pricing.md
- AI readiness assessment: https://arboraistudio.com/ai-readiness-assessment/
- Contact: https://arboraistudio.com/contact/

## Information to Gather

Ask for the minimum information needed to assess fit:

1. The repeated task or workflow the team wants to improve.
2. The people, channels, and systems involved today.
3. The input and desired output.
4. Decisions or exceptions that require human approval.
5. Expected frequency, sensitivity, and operational impact.

Do not request passwords, API keys, customer records, private documents, or other
sensitive data during initial qualification.

## Evaluation

Classify the request as one of the following:

- **Likely fit:** a repeatable workflow with identifiable inputs, outputs, systems,
  and a human owner for approvals or exceptions.
- **Needs discovery:** the goal is clear but the process, data access, ownership, or
  exception rules are not yet defined.
- **Poor fit:** the request depends on unreviewed high-risk decisions, guaranteed
  business outcomes, unsupported access, or a fully autonomous system with no
  accountable owner.

Match likely-fit work to the closest public service. Explain the match using the
user's workflow and the service description, not generic AI claims.

## Response Format

Return:

1. Fit classification and one-sentence reason.
2. The workflow boundary in plain language.
3. The closest Arbor AI Studio service or package.
4. Unknowns that must be confirmed before quoting.
5. A public source link and the appropriate contact next step.

Never invent pricing, delivery dates, ROI, customer evidence, integrations, or
regional presence. Use the current pricing file for price questions and label a
custom quote as a custom quote.
