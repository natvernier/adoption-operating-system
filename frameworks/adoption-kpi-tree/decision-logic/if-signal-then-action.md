# If-Signal-Then-Action Logic

A KPI is only useful if it can change a decision, conversation or operating action.

The if-signal-then-action pattern turns adoption measurement into decision logic.

It helps teams move from passive reporting to active steering.

## Core principle

An adoption signal should not only describe what happened.

It should help the organization decide what to do next.

```text
If a signal does not support a decision,
it may be reporting noise.
```

## Basic pattern

Use this structure:

```text
If [signal],
then [interpretation],
therefore [action].
```

A more complete version:

```text
If [observable signal appears],
then this may indicate [interpretation],
therefore we will [action],
owned by [owner],
reviewed in [forum],
by [timeframe].
```

## Why this matters

Many adoption dashboards show activity but do not create better decisions.

Examples:

```text
Training completion: 84%
Monthly active users: 1,200
Prompt usage: +36%
Template downloads: 400
```

These numbers may be useful, but they do not yet answer:

```text
What does this mean?
Is this good or bad?
Compared to what?
For which role?
In which workflow?
What should we do next?
Who owns the response?
```

The if-signal-then-action pattern adds interpretation and ownership.

## Template

```text
If:
[Describe the observable signal.]

Then this may indicate:
[Describe the interpretation.]

Action:
[Describe the operating action.]

Owner:
[Name the responsible role or team.]

Decision forum:
[Where this will be reviewed.]

Review timeframe:
[When this will be reviewed again.]

Related countermetric:
[What should be watched to avoid one-sided optimization.]
```

## Example 1: Training without activation

```text
If:
Training completion is high but first meaningful use is low.

Then this may indicate:
Enablement is not translating into real workflow behavior.

Action:
Replace generic training with role-specific examples, practice tasks and manager prompts.

Owner:
Enablement lead and manager.

Decision forum:
Rollout check-in.

Review timeframe:
Two weeks after updated enablement.

Related countermetric:
Repeat use after first meaningful use.
```

## Example 2: Usage without workflow change

```text
If:
Tool usage increases but eligible workflows continue to use the old process.

Then this may indicate:
The tool is being added on top of existing work instead of changing the workflow.

Action:
Review workflow fit, remove duplicate steps and redesign the process around the capability.

Owner:
Product/platform owner and workflow owner.

Decision forum:
Adoption review.

Review timeframe:
Next review cycle.

Related countermetric:
Old-workflow persistence.
```

## Example 3: High usage with low quality

```text
If:
Usage increases but review rejection rate also increases.

Then this may indicate:
Adoption volume is outpacing proficiency.

Action:
Pause expansion, improve input quality, clarify review criteria and update examples.

Owner:
Workflow owner and quality/review owner.

Decision forum:
Adoption and quality review.

Review timeframe:
Before next scaling decision.

Related countermetric:
Correction rate after review.
```

## Example 4: More escalations after rollout

```text
If:
Escalations increase after the new workflow is introduced.

Then this may indicate:
Hidden uncertainty is becoming visible.

Action:
Classify escalation types before treating the increase as failure.

Owner:
Governance owner.

Decision forum:
Governance review.

Review timeframe:
After classification of escalation patterns.

Related countermetric:
Severity and repetition of escalation types.
```

## Example 5: Confidence without clarity

```text
If:
Users report confidence but cannot explain review responsibilities.

Then this may indicate:
Adoption may be performative rather than operational.

Action:
Clarify decision rights, human judgment points and review gates.

Owner:
Governance owner and enablement lead.

Decision forum:
Adoption review.

Review timeframe:
Next enablement iteration.

Related countermetric:
Sensitive outputs without documented review.
```

## Example 6: Speed with downstream effort

```text
If:
Cycle time improves but reviewer workload increases.

Then this may indicate:
Speed gains are shifting work downstream.

Action:
Improve pre-review quality gates and input standards before scaling further.

Owner:
Workflow owner and reviewer lead.

Decision forum:
Quality review.

Review timeframe:
After two workflow cycles.

Related countermetric:
Review effort per output.
```

## Example 7: Reuse without relevance

```text
If:
Reusable templates are frequently used but outputs become generic.

Then this may indicate:
Reuse is improving efficiency but weakening contextual judgment.

Action:
Add context checkpoints, audience criteria or domain-specific adaptation steps.

Owner:
Template owner and subject-matter expert.

Decision forum:
Workflow review.

Review timeframe:
After updated template use.

Related countermetric:
Audience or use-case fit.
```

## Example 8: Local champion dependency

```text
If:
Adoption is strong in one team but weak elsewhere.

Then this may indicate:
Adoption depends on a local champion rather than on a reusable operating pattern.

Action:
Identify the champion’s practices and translate them into templates, rituals or enablement materials.

Owner:
Adoption lead and manager.

Decision forum:
Scaling review.

Review timeframe:
Before expanding to additional teams.

Related countermetric:
Adoption beyond the initial team.
```

## Example 9: High trust but low use

```text
If:
Users trust the new capability but do not use it frequently.

Then this may indicate:
The issue may be workflow relevance, access, effort or timing rather than resistance.

Action:
Investigate workflow integration, task triggers and usability.

Owner:
Product/platform owner.

Decision forum:
Product adoption review.

Review timeframe:
After workflow interviews or feedback review.

Related countermetric:
First meaningful use and repeat use.
```

## Example 10: Policy without operational clarity

```text
If:
A policy exists but teams repeatedly ask how to apply it in specific cases.

Then this may indicate:
Governance is too abstract to guide daily work.

Action:
Translate policy into workflow-specific examples, decision rules and escalation paths.

Owner:
Governance owner.

Decision forum:
Governance and adoption review.

Review timeframe:
After guidance update.

Related countermetric:
Repeated governance questions.
```

## Action types

Use one of these action types to classify the response.

### Scale

Expand the workflow, pattern or capability.

Use when adoption, quality, value and risk signals are stable enough to move beyond the current scope.

### Pause

Stop expansion until quality, risk, trust or clarity improves.

Use when adoption is growing but the supporting operating system is not ready.

### Redesign

Change the workflow, template, interface, handover or process.

Use when signals show friction, workarounds, duplicated effort or poor workflow fit.

### Clarify

Improve decision rights, ownership, criteria, communication or expectations.

Use when people are willing to adopt but uncertain about how, when or who decides.

### Train

Build capability through targeted enablement.

Use when signals show skill gaps, repeated basic questions or weak first meaningful use.

### Govern

Add or improve guardrails, review gates, escalation paths or documentation.

Use when signals show unmanaged risk, unclear accountability or sensitive use cases.

### Investigate

Collect more evidence before acting.

Use when a signal is visible but ambiguous.

### Standardize

Turn a successful pattern into reusable guidance.

Use when local adoption is working and the pattern can be transferred.

### Stop

End a workflow, metric, pilot or practice that is not useful, safe or worth maintaining.

Use when adoption is weak, value is unclear and redesign is not justified.

### Observe

Continue monitoring when the signal is visible but not yet stable.

Use when early evidence exists but a decision would be premature.

## Blank reusable block

```text
If:
[Signal]

Then this may indicate:
[Interpretation]

Action:
[Action]

Owner:
[Owner]

Decision forum:
[Forum]

Review timeframe:
[Timeframe]

Related countermetric:
[Countermetric]
```

## Final check

Before adding an if-signal-then-action rule to the KPI tree, ask:

```text
Would this signal change what we do next?
Who owns the response?
What countermetric prevents false success?
When will we review it again?
```

If these questions cannot be answered, the signal may need to be redefined.
