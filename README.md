# AI Governance Workflow, demonstrated end to end

A narrated walkthrough of an AI governance process I built: intake, screening, scoring, tiered oversight, and the audit trail an AI system leaves behind, shown on one real case.

<video src="media/governance-flow-demo.mp4" controls muted width="600"></video>

2 minutes 39 seconds. Watch it [directly](media/governance-flow-demo.mp4) if the player above doesn't load.

## What it shows

A sample system, an HR model that ranks employees for promotion and layoff decisions, moves through a governance workflow from the moment it's submitted to the moment its first audit finding gets resolved:

- **Intake.** Every system gets logged before it goes live, with what data it touches and how big the decision is.
- **Screening.** A check against uses the law forbids outright, and a check for conflicts across jurisdictions.
- **Scoring and tiering.** The answers to a fixed set of questions produce a number, and the number decides who signs off and how often the system gets reviewed.
- **The register and the clock.** Every system lands in one record, and its legal deadlines start counting against the frameworks that apply to it: the EU AI Act, the NIST AI Risk Management Framework, and ISO/IEC 42001.
- **The audit.** The system's first scheduled review finds a real fairness gap, traces it to its cause, and pauses the system until a fix is verified.

## Why

Most AI governance advice stays at the policy level: what a company should do. This demonstrates what doing it actually looks like, the sequence of concrete steps, end to end, on a case with a real finding in it rather than a hypothetical.

## Access

This repository holds the demonstration only. The underlying toolkit is mine, used in my own governance engagements, and isn't distributed or available for download. If you want to talk about how something like this would work for your organization, reach out.

## Contact

David E. Wilson · [voxdw.com](https://voxdw.com) · [LinkedIn](https://www.linkedin.com/in/daviderinwilson)
