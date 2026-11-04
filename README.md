# Microsoft 365 AI Agents Management 101

A beginner learning lab by **Sebastián Zamorano (Kaz)**.

Five makers. Twenty small agents. Similar jobs, unclear names, and a growing inventory. This exercise makes agent proliferation visible, then introduces the questions needed to manage it.

You will learn to identify an agent by more than its display name, compare overlapping purposes, record accountable owners, inspect data access, and distinguish a configured control from a tested outcome.

## Start here

1. [Understand the scenario](docs/01-scenario.md).
2. [Build the small agents](docs/02-build-the-agents.md).
3. [Inspect the administrative inventory](docs/03-inventory-and-controls.md).
4. [Review the evidence and limitations](docs/04-observations.md).
5. [Run the classroom exercise and clean up](docs/05-exercise-and-cleanup.md).
6. [Assign simple operating responsibilities](docs/06-operating-model.md).

Use the [agent recipes](lab/agent-recipes.json), [inventory](lab/agent-inventory.csv), and [review worksheet](lab/review-worksheet.csv). Recipes are authoring inputs, **not** a supported bulk-import package or deployment script.

## Current lab status

Evidence date: **November 3, 2026**, America/Bogota. This is a controlled educational exercise using synthetic content. Read the observation log for the exact completed work. Planned recipes do not imply deployed agents.

Current batch: four private agents created by Maker A and tested with synthetic inputs. Slides required a narrower text-only prompt after an extensive generation was stopped. The remaining sixteen recipes are prepared. Read the observations before interpreting these tests as quality or enforcement guarantees.

| Label | Meaning |
|---|---|
| Prepared | Instructions, sample data, or a procedure exist |
| Created | The product confirmed agent creation |
| Tested | We submitted a recorded test and inspected its response |
| Observed | We inspected a specific setting, field, or screen |
| Pending | Execution or effective enforcement has not been verified |

This repository documents learning, not a production deployment or a universal inventory guarantee. Interface labels and available controls can vary with licensing and rollout. No Azure subscription or consumption billing was configured for the initial exercise.

## Why this lab exists

These articles provide the author's framing:

- [Are We Governing Information or Configuring Tools?](https://www.linkedin.com/pulse/one-approach-enough-we-governing-information-tools-sebastian-zamorano-emsbe)
- [Six Months Later, No One Knew How Many Agents Existed](https://www.linkedin.com/pulse/one-approach-enough-six-months-later-knew-how-many-agents-zamorano-pg9ne)

The second article explicitly presents a fictional story. Our lab illustrates its inventory problem with real product observations. It does not reproduce the story's incidents or validate its statistics. The first article connects governance requirements with implementation and evidence. Here, learners practice making that connection through a small exercise.

## Scope

The first path uses Agent Builder in Microsoft 365 Copilot. Agents prepare email drafts, meeting minutes from supplied notes, structured document text, and presentation outlines. Actual email delivery, autonomous actions, production content, and advanced reporting infrastructure are outside this first lab.

The earlier *AI Management Project: Administration, Operations, Governance, and Reporting* document (v1.0, July 24, 2026) informed the ownership and review questions. It is a broader design reference, not a list of controls tested here. Its command/API catalog has not been adopted as executable lab automation.

[Official sources and verification scope](docs/sources.md). The existing [repository license](LICENSE) is preserved. Microsoft product names and interface imagery remain attributable to their respective owners.
