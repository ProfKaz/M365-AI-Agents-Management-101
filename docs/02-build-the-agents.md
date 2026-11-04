# 2. Build the small agents

## Prerequisites

Use an authorized test tenant, a maker account with access to Agent Builder, and a separate administrative account for inventory review. In our lab the user reported Microsoft 365 Copilot add-on, Microsoft 365 E5 (no Teams), and Teams Enterprise for the pilot maker. We verified authoring access interactively. We did not independently export assigned licensing SKUs.

Microsoft describes Agent Builder as a declarative-agent authoring experience for straightforward scenarios. External-service actions require another development route such as copying to Copilot Studio. Check licensing and availability before repeating this lab. [Agent Builder overview](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-builder).

## First agent

1. Sign in as the intended maker and verify the account name.
2. In Copilot, open **Agents & Skills**, then **New agent**. If the introductory conversational screen appears, use **Skip** to open configuration.
3. Enter the name, description, and instructions from the recipe. Confirm that the instructions actually remain in the editor after leaving it.
4. Inspect **Knowledge**. In our observed experience, Cloud files, Outlook, Teams, and Web search started enabled. Turn each off for this text-only lab. Keep Copilot connectors off and leave attachments and skills empty.
5. Wait for the saved-draft indication. Review the configuration and select **Create**.
6. Record creation success and the sharing state. For the pilot, the product stated that the agent was private and available only to its creator.
7. Select **Start chat**, submit the recipe's synthetic test, and inspect the response. Record the actual result, including unexpected behavior.
8. Save the agent's identifier and URL in the private facilitator inventory. Do not rely on its display name.

Disabling sources is an authoring configuration choice. An instruction such as “use only the supplied text” is behavioral guidance and is not proof of an access boundary. Our initial test did not attempt to exhaustively validate retrieval isolation.

## Repeat with controlled overlap

Build the remaining three recipes for the first maker. Then repeat the four families with the other makers. Check the account before every batch. Use the inventory to distinguish prepared, created, and tested rows. Do not mark all twenty as created because twenty recipes exist.

The recipes retain Spanish instructions and sample inputs to match the live Spanish-language session. The guide explains the procedure in English.

## What these agents do

| Family | Input | Output | Human check |
|---|---|---|---|
| Email | Recipient, goal, date, tone | Draft subject and body | Facts, recipient, commitments |
| Minutes | Synthetic meeting notes | Decisions and action list | Unsupported decisions or inferred owners |
| Document | Short synthetic text | Headings, lists, consistent wording | Meaning preserved |
| Presentation | Topic and audience | Five-slide outline | Claims and invented statistics |

The document and presentation recipes request structured content. They do not claim to modify an existing Word or PowerPoint file. The native experience may expose additional file-generation capabilities; those require their own recorded tests.
