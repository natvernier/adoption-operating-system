# Adoption Signal Categories

Adoption is not one signal.

It is a pattern of signals across usage, activation, workflow change, capability, quality, value, risk, trust, governance and scaling.

This folder defines the signal categories used in an Adoption KPI Tree.

## Purpose

The purpose of adoption signal categories is to help teams observe adoption as a work-system pattern, not only as activity.

A useful adoption measurement system does not only ask:

```text
Are people using it?
```

It asks:

```text
Are the right people using the new capability
in the right workflows
with enough proficiency
to create value
without creating unmanaged risk?
```

## Core principle

A single adoption signal is rarely enough.

Usage without workflow context is weak.

Value without risk visibility is incomplete.

Risk without learning logic can become a blocker.

Governance without operational evidence may remain policy-only.

Scaling without quality stability can create adoption debt.

A strong Adoption KPI Tree combines different signal types so adoption becomes visible, interpretable and actionable.

## Signal categories

This folder contains the following signal categories:

| File                    | Focus                                                               |
| ----------------------- | ------------------------------------------------------------------- |
| `usage-signals.md`      | Whether a tool, template, workflow or capability is being used      |
| `activation-signals.md` | Whether people move from exposure to first meaningful use           |
| `workflow-signals.md`   | Whether work is actually changing                                   |
| `capability-signals.md` | Whether people understand how to use the capability appropriately   |
| `quality-signals.md`    | Whether outputs, decisions or processes improve or remain reliable  |
| `value-signals.md`      | Whether adoption creates meaningful benefit                         |
| `risk-signals.md`       | Where adoption creates exposure, ambiguity or misuse                |
| `trust-signals.md`      | Whether people believe the system can be used safely and usefully   |
| `governance-signals.md` | Whether adoption is becoming manageable, reviewable and accountable |
| `scaling-signals.md`    | Whether adoption can move beyond pilots and local champions         |

## How to use these categories

Do not use every signal category for every KPI tree.

Choose the categories that matter for the workflow, risk level and decision context.

A lightweight adoption KPI tree may only need:

```text
Usage signals
Workflow signals
Quality signals
Operating actions
```

A mature AI adoption KPI tree may need:

```text
Usage signals
Activation signals
Workflow signals
Capability signals
Quality signals
Value signals
Risk signals
Trust signals
Governance signals
Scaling signals
```

The aim is not measurement volume.

The aim is decision clarity.

## Recommended selection logic

Use this guide to decide which signal categories matter.

| If the adoption question is...                | Use these signal categories         |
| --------------------------------------------- | ----------------------------------- |
| Are people using it?                          | Usage, activation                   |
| Is it entering real work?                     | Activation, workflow                |
| Are people using it appropriately?            | Capability, quality, governance     |
| Is it creating benefit?                       | Value, quality, workflow            |
| Is it creating unmanaged exposure?            | Risk, governance, trust             |
| Is it trusted enough to be used meaningfully? | Trust, capability, governance       |
| Can it scale beyond a pilot?                  | Scaling, quality, governance, value |
| Are we ready to expand?                       | Scaling, risk, quality, value       |

## Signal interpretation

Adoption signals should be interpreted together.

For example:

```text
High usage + low quality
= adoption volume may be outpacing proficiency.
```

```text
Low usage + high trust
= the issue may be workflow relevance, timing, access or effort.
```

```text
More escalations + clearer escalation categories
= uncertainty may be becoming visible in a useful way.
```

```text
Faster cycle time + higher review effort
= speed gains may be shifting work downstream.
```

This is why signal categories should connect to decision logic.

## Relationship to decision logic

Signal categories describe what to observe.

Decision logic describes what to do with what is observed.

A useful adoption signal should eventually support this pattern:

```text
If [signal],
then [interpretation],
therefore [action].
```

## Final principle

A good adoption signal helps the organization decide what to scale, pause, redesign, clarify, govern or stop.

```text
Adoption measurement is mature when it helps the organization understand how work is changing and what should happen next.
```
