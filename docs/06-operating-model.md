# 6. A small operating model

The earlier AI Management Project document describes a much broader administrative and reporting program. For this beginner lab, use a small review loop with an explicit owner and evidence.

| Responsibility | Accountable role | Output |
|---|---|---|
| Explain purpose and decide whether overlap is justified | Business owner | Short use-case statement and decision |
| Maintain instructions, configuration and dependencies | Technical owner or maker | Versioned recipe and inventory |
| Approve data use | Data owner | Source and audience decision |
| Apply authorized administrative changes | Administrator | Change record and relevant validation |
| Review use and decide continuation | Business owner with administrator | Review date, findings and next action |

One person may cover several roles in a small team, but write down who makes each decision. The five makers and the administrator are lab roles, not automatic assignments of business accountability.

## Suggested cadence

At creation, register purpose, identity/creator, audience, data, actions and a review date. Before broader sharing, review the requirements and test the intended access and behavior. During operation, review changes, meaningful use, issues and cost signals where available. At retirement, preserve evidence and resolve dependencies before deletion. This is a suggested teaching model, not a product-enforced workflow.

## A useful change record

Record the agent ID, actor, time, requirement, previous setting, new setting, test and observed outcome. Include unexpected results and propagation delays. The lab's read-only inventory inspection is already useful evidence; it does not establish that blocking, DLP, access reviews or an incident pipeline have been configured or tested.

Advanced reporting across Purview, Entra, Defender, Power Platform and Azure can follow later. This first exercise does not need an API collector, service principal, Key Vault access or Azure resource deployment to teach ownership and inventory.
