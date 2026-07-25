# When a Correct AI Output Is Still Not a Finding

An AI output can be completely correct and still not be a finding.

An AI system produces an **artifact**: a score, label, match, summary, classification, or other machine-generated output. A **finding** requires an accountable evaluator to determine what that artifact establishes in relation to the evidence, context, scope, and investigative proposition.

## A simple example

Suppose an AI-assisted insider-threat system reviews legitimate access logs and reports:

> **Artifact:** Employee X accessed 147 customer records between 01:10 and 02:05, significantly above the employee's established baseline.

Assume the system worked exactly as designed. The records, timestamps, and baseline calculation are correct, and the interaction is fully logged. There has been no model malfunction or technical failure.

The output nevertheless does not establish misconduct. The employee may have been conducting an approved reconciliation, responding to an incident, covering another employee's workload, or performing another authorized task that generates unusual access.

An analyst must therefore examine the employee's role and authorization, operational tickets and change records, historical activity, relevant system logs, and other appropriate evidence. That evaluation may support a finding such as:

> **Finding:** Employee X accessed customer records outside the requirements of the employee's assigned duties, without an associated operational request or authorization.

The underlying access artifact has not changed. What has changed is the evidentiary conclusion that the available record can support.

## The evidentiary chain

The appropriate sequence is:

**Evidence → AI processing → Artifact → Human evaluation and corroboration → Finding → Decision or action**

The dangerous shortcut is:

**Evidence → AI processing → “Finding” → Action**

The shortcut collapses a machine output, an investigative conclusion, and an organizational decision into a single step.

## Four distinct stages

1. **Artifact:** “The account accessed 147 records.”
2. **Validated artifact:** “The underlying logs confirm that 147 records were accessed.”
3. **Finding:** “The access was unauthorized and inconsistent with the employee's assigned duties.”
4. **Organizational determination:** “The conduct constitutes misconduct under the applicable policy.”

Validation confirms the artifact's technical or factual accuracy. It does not, by itself, establish the contextual proposition required for a finding.

## Other examples

- A fraud model reports a 94% probability of fraud. That is an artifact, not a finding that the customer committed fraud.
- A facial-recognition system reports a 97% candidate similarity. That is an artifact, not an identification finding.
- An AI forensic tool reports that a communication appears consistent with data exfiltration. That is an artifact, not a finding that an employee stole information.
- A malware classifier labels a file malicious with 99.2% confidence. That is an artifact; investigation may establish that the file was an authorized penetration-testing tool.

None of these examples requires the AI system to be wrong.

## What “promotion” means

Promotion is not merely the act of reviewing an artifact. It occurs when an artifact is assigned evidentiary meaning beyond what its native technical proposition establishes.

The key distinction is therefore not simply between automated and human work. It is between:

- what the system established;
- how the output represented that warrant;
- what a person attributed to the output; and
- what conclusion or action the organization ultimately adopted.

In the correct-output case, technical accuracy is necessary to classifying the incident as artifact-to-finding promotion, but accuracy is not sufficient to justify promotion.

## Proposed control

> **Artifact-to-Finding Promotion Control:** An AI-generated artifact must not be treated as an investigative finding solely because the system operated as designed or the output was technically accurate. Promotion to a finding requires accountable human evaluation of the artifact against its provenance, stated scope, represented warrant, corroborating evidence, relevant context, plausible defeaters, and the investigative proposition being tested.

This is more specific than a general instruction to “keep a human in the loop.” It is an evidentiary rule governing when machine-produced information may acquire investigative meaning.

## Further reading

Kevin V. Watson, *Artifact-to-Finding Promotion: Evidentiary Requirements for Harm from Correctly Functioning AI Systems*, Working Paper, Version 1.0 (2026).  
https://doi.org/10.5281/zenodo.21543521
