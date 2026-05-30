# Decision Thresholds

Decision thresholds define when an adoption signal becomes actionable.

They help teams avoid two common problems:

1. reacting too quickly to weak or noisy signals
2. ignoring signals until they become serious problems

A decision threshold does not need to be mathematically perfect.

It needs to be clear enough to support timely, responsible action.

## Core principle

A signal becomes useful when the organization knows what level of change should trigger attention, investigation or action.

```text
A KPI without a threshold can show movement.
A KPI with a threshold can support a decision.
```

## Why thresholds matter

Adoption signals are often ambiguous.

For example:

```text
Escalations increased.
Review effort increased.
Usage dropped.
Confidence improved.
More people used the template.
Old workarounds remain.
```

None of these signals is automatically good or bad.

The threshold helps the team decide:

```text
Should we observe?
Should we investigate?
Should we act?
Should we escalate?
Should we stop?
```

## Threshold levels

Use four simple threshold levels.

```text
Watch
Investigate
Act
Escalate
```

## 1. Watch

Use `Watch` when a signal is visible but not yet stable or severe.

### Meaning

The signal may matter, but it is too early to interpret strongly.

### Use when

* the signal appears once
* the trend is unclear
* the affected scope is small
* the risk level is low
* more data or examples are needed
* no immediate decision is required

### Example

```text
Signal:
Support questions about the new workflow increase during the first rollout week.

Threshold:
Watch.

Interpretation:
This may be normal early learning.

Action:
Collect question themes before changing the workflow.
```

## 2. Investigate

Use `Investigate` when a signal repeats, affects a priority workflow or creates interpretation uncertainty.

### Meaning

The signal may indicate friction, risk, value or learning, but the cause is unclear.

### Use when

* the signal appears repeatedly
* different teams interpret it differently
* the impact is unclear
* qualitative feedback is needed
* the signal affects a priority workflow
* there is a gap between usage and quality, value or trust

### Example

```text
Signal:
First meaningful use is high, but repeat use is low after 30 days.

Threshold:
Investigate.

Interpretation:
Curiosity exists, but sustained value may be missing.

Action:
Interview users and review workflow friction, trust and task relevance.
```

## 3. Act

Use `Act` when a signal clearly affects adoption quality, workflow performance, user capability, value or scaling readiness.

### Meaning

The signal is strong enough to justify an operating response.

### Use when

* the same issue repeats across users or teams
* quality or value is affected
* adoption is blocked by a known cause
* old workarounds persist
* review effort increases in a pattern
* enablement gaps are clear
* scaling readiness is affected

### Example

```text
Signal:
Usage increases, but review rejection rate also increases.

Threshold:
Act.

Interpretation:
Adoption volume is outpacing proficiency.

Action:
Pause expansion, improve input quality and update review criteria.
```

## 4. Escalate

Use `Escalate` when a signal affects accountability, sensitive use cases, compliance, trust, unmanaged risk or leadership-level decisions.

### Meaning

The signal exceeds the local team’s decision authority or risk tolerance.

### Use when

* sensitive use cases are involved
* review gates are bypassed
* accountability is unclear
* policy boundaries are crossed
* unmanaged tools are used in high-risk workflows
* risk cannot be resolved locally
* scaling decisions require leadership or governance review

### Example

```text
Signal:
Sensitive AI-supported outputs are created without documented human review.

Threshold:
Escalate.

Interpretation:
Accountability and review requirements are unclear or not followed.

Action:
Escalate to governance owner and pause use in sensitive cases until review rules are clarified.
```

## Threshold matrix

| Threshold   | Meaning                                                               | Typical response                                   |
| ----------- | --------------------------------------------------------------------- | -------------------------------------------------- |
| Watch       | Signal visible but not stable                                         | Monitor and collect examples                       |
| Investigate | Signal repeated or ambiguous                                          | Analyze causes and gather evidence                 |
| Act         | Signal affects workflow, quality, value or adoption                   | Change workflow, enablement, guidance or ownership |
| Escalate    | Signal affects accountability, sensitive use, trust or unmanaged risk | Move to governance, leadership or risk forum       |

## Threshold design questions

Use these questions when defining thresholds.

```text
At what point does this signal need attention?
At what point does this signal require investigation?
At what point does this signal require action?
At what point does this signal need escalation?
Who has authority to act?
Who needs to be informed?
What countermetric should be reviewed before acting?
```

## Example threshold table

| Signal                | Watch                          | Investigate                      | Act                                            | Escalate                                                            |
| --------------------- | ------------------------------ | -------------------------------- | ---------------------------------------------- | ------------------------------------------------------------------- |
| First meaningful use  | Early use visible but uneven   | Low activation in target roles   | Activation remains low after enablement update | Critical role group does not adopt before scaling decision          |
| Review rejection rate | Slight increase after rollout  | Repeated rejection themes        | Rejection rate affects workflow throughput     | Sensitive outputs fail review or bypass review                      |
| Escalations           | Initial increase after rollout | Repeated questions by type       | Escalations block workflow progress            | Escalations involve policy, legal, sensitive data or accountability |
| Old workarounds       | Local exceptions visible       | Workarounds repeat across teams  | Workarounds undermine workflow adoption        | Workarounds bypass required controls                                |
| Confidence            | Mixed feedback                 | Confidence low in priority roles | Low confidence blocks adoption                 | Trust concerns affect sensitive or leadership-critical use cases    |
| Template reuse        | Early use visible              | Reuse concentrated in one team   | Low reuse after discoverability improvements   | Teams create unmanaged alternatives for sensitive workflows         |

## Quantitative and qualitative thresholds

Not every threshold needs a precise number.

Some adoption signals require qualitative interpretation.

### Quantitative threshold examples

```text
Less than 30% of target users complete first meaningful use within the first month.
Review rejection rate increases by more than 20%.
Repeat use after 30 days falls below the expected baseline.
More than 50% of support questions concern the same workflow step.
```

### Qualitative threshold examples

```text
Users cannot explain when human review is required.
Managers do not know how to discuss adoption in team rituals.
Reviewers report recurring issues with input quality.
Governance questions repeat across teams.
Teams create unofficial workarounds for the same process step.
```

## Thresholds by adoption stage

Thresholds should change as adoption matures.

## Exploration

At this stage, signals are weak and learning-oriented.

Focus on:

* use case relevance
* early friction
* perceived usefulness
* risk assumptions
* workflow fit

Threshold tendency:

```text
More Watch and Investigate.
Less Act and Escalate unless risk is high.
```

## Pilot

At this stage, the goal is to test whether adoption can work in a controlled context.

Focus on:

* first meaningful use
* quality after review
* workflow fit
* support needs
* early governance questions

Threshold tendency:

```text
Investigate repeated patterns quickly.
Act when quality or workflow friction blocks learning.
```

## Early rollout

At this stage, adoption moves beyond a small group.

Focus on:

* repeat use
* role-specific adoption
* manager support
* review effort
* escalation patterns
* old-workflow persistence

Threshold tendency:

```text
Act on repeated friction.
Escalate unclear accountability or sensitive use.
```

## Stabilization

At this stage, adoption should become part of everyday work.

Focus on:

* sustained use
* quality stability
* reduced support dependency
* reusable patterns
* governance routine
* value realization

Threshold tendency:

```text
Act on instability.
Standardize what works.
Remove noisy metrics.
```

## Scaling

At this stage, adoption should transfer across teams or workflows.

Focus on:

* repeatability
* quality across contexts
* role readiness
* governance capacity
* pattern reuse
* countermetrics

Threshold tendency:

```text
Escalate scaling risks early.
Do not scale if quality, trust or governance signals are unstable.
```

## Threshold anti-patterns

Avoid these mistakes.

### Thresholds that are too vague

Weak:

```text
If adoption is low, act.
```

Better:

```text
If first meaningful use remains low in target roles after role-specific enablement, investigate workflow relevance and manager support.
```

### Thresholds that only reward volume

Weak:

```text
If usage increases, scale.
```

Better:

```text
If usage increases and quality, risk and repeat-use signals are stable, consider scaling.
```

### Thresholds without ownership

Weak:

```text
If review issues increase, improve quality.
```

Better:

```text
If repeated review issues appear in two review cycles, the workflow owner and reviewer lead update input criteria before the next rollout wave.
```

### Thresholds that treat risk as failure too early

Weak:

```text
If escalations increase, the rollout failed.
```

Better:

```text
If escalations increase, classify them by type, severity and repeat pattern before deciding whether this is failure, learning or improved visibility.
```

## Final principle

Thresholds should not make the organization more rigid.

They should make adoption easier to steer.

```text
Good thresholds help teams decide when to observe, investigate, act or escalate.
```
