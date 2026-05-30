# Decision Logic

Decision logic turns adoption measurement into operating action.

It defines how adoption signals should be interpreted, when they should trigger decisions and what actions should follow.

This folder is part of the Adoption KPI Tree framework.

## Purpose

The purpose of decision logic is to prevent adoption measurement from becoming passive reporting.

A metric is only useful if it helps the organization decide what to do next.

```text
An Adoption KPI Tree is not a reporting structure.
It is a decision structure.
```

## Core idea

Many organizations measure adoption through activity:

* users trained
* tools accessed
* sessions completed
* prompts submitted
* templates downloaded
* pilots launched
* dashboards viewed

These signals can be useful, but they are not enough.

Decision logic asks:

```text
What does this signal mean?
What should we do if it changes?
Who owns the response?
When should we review it again?
What countermetric prevents false success?
```

## Folder contents

This folder contains three supporting files.

### `if-signal-then-action.md`

A practical pattern library for turning adoption signals into actions.

Use this file when you need to define:

```text
If [signal],
then [interpretation],
therefore [action].
```

It includes examples for:

* training without activation
* usage without workflow change
* high usage with low quality
* more escalations after rollout
* confidence without clarity
* speed with downstream effort
* reuse without relevance
* local champion dependency
* policy without operational clarity

### `decision-thresholds.md`

A guide for deciding when a signal becomes actionable.

It defines four threshold levels:

```text
Watch
Investigate
Act
Escalate
```

Use this file when you need to clarify:

* when to keep observing
* when to investigate
* when to change the workflow
* when to escalate to governance or leadership
* when a signal is strong enough to influence scaling

### `interpretation-patterns.md`

A guide for avoiding false conclusions.

It explains why adoption signals are rarely self-explanatory.

Use this file when you need to interpret signals such as:

* high usage
* low usage
* more escalations
* faster cycle time
* higher confidence
* high training completion
* increased questions
* increased reuse
* local adoption success
* no visible risk signals

## How decision logic fits into the Adoption KPI Tree

The Adoption KPI Tree connects:

```text
Strategic ambition
→ Adoption outcomes
→ Behavioral and workflow signals
→ Quality, value and risk indicators
→ Operating actions
```

Decision logic sits between signals and operating actions.

It helps teams avoid jumping directly from a metric to a conclusion.

```text
Signal
→ Interpretation
→ Threshold
→ Action
→ Owner
→ Review rhythm
```

## Decision logic pattern

Use this basic structure:

```text
If [signal],
then [interpretation],
therefore [action].
```

Use the extended structure when ownership and review are needed:

```text
If [observable signal appears],
then this may indicate [interpretation],
therefore we will [action],
owned by [owner],
reviewed in [forum],
by [timeframe].
```

## Example

```text
If usage increases but review rejection rate also increases,
then adoption volume may be outpacing proficiency.

Action:
Pause expansion, improve input quality, clarify review criteria and update examples.
```

This is stronger than reporting:

```text
Usage increased by 34%.
```

Because the signal now supports a decision.

## Decision action types

Decision logic usually leads to one of these action types:

| Action type | Meaning                                                     |
| ----------- | ----------------------------------------------------------- |
| Scale       | Expand what works                                           |
| Pause       | Stop expansion until quality, trust or risk improves        |
| Redesign    | Change the workflow, template, handover or process          |
| Clarify     | Improve decision rights, ownership or criteria              |
| Train       | Build targeted capability                                   |
| Govern      | Add or improve guardrails, review gates or escalation paths |
| Investigate | Gather more evidence before acting                          |
| Standardize | Turn a successful pattern into reusable guidance            |
| Stop        | End what is not useful, safe or worth maintaining           |
| Observe     | Continue monitoring until the signal stabilizes             |

## Good decision logic should define

For every important adoption signal, define:

```text
Signal:
What did we observe?

Interpretation:
What might it mean?

Threshold:
Is this a Watch, Investigate, Act or Escalate signal?

Action:
What should happen next?

Owner:
Who is responsible?

Forum:
Where is it reviewed?

Countermetric:
What prevents one-sided optimization?

Review rhythm:
When do we revisit the signal?
```

## Common anti-patterns

Avoid these patterns.

### KPI without action

```text
Monthly active users increased.
```

Better:

```text
If monthly active users increase but repeat workflow use remains low,
then adoption may be shallow.

Action:
Review workflow fit and first meaningful use.
```

### Threshold without owner

```text
If review issues increase, improve quality.
```

Better:

```text
If the same review issue appears in two review cycles,
then the workflow owner and reviewer lead update the input criteria before the next rollout wave.
```

### Usage without countermetric

```text
If usage increases, scale.
```

Better:

```text
If usage increases and quality, risk and repeat-use signals remain stable,
then consider scaling.
```

### Risk treated only as failure

```text
If escalations increase, the rollout failed.
```

Better:

```text
If escalations increase,
then classify escalation types before deciding whether this is failure, learning or improved visibility.
```

## Review questions

Use these questions in adoption reviews:

```text
What changed in the work system?
What does this signal probably mean?
What else could it mean?
Which related signals should we check?
Is this a Watch, Investigate, Act or Escalate signal?
Who owns the response?
What action should happen next?
What countermetric should we monitor?
When should we review this again?
```

## Relationship to operating rituals

Decision logic should be reviewed in recurring operating rituals.

Possible review rhythms:

```text
Weekly during rollout
Biweekly during early adoption
Monthly during stabilization
Quarterly during scaling or portfolio review
```

The review should not only ask:

```text
Did the numbers improve?
```

It should ask:

```text
What did we learn about the work system?
What should we change because of what we learned?
```

## Final principle

The purpose of adoption measurement is not to prove that transformation activity happened.

The purpose is to help the organization decide what to scale, pause, redesign, clarify, govern or stop.

```text
The value of an adoption KPI is not the number itself.
It is the action the organization is willing to take when the signal changes.
```
