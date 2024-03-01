## Context and Problem Statement
Avoid complexity in the system under construction
## Decision Drivers
* Divide the overall system into logical building blocks
* Ensure the ability to change system parts without affecting others
## Considered Options
1. Layers
2. Components
3. Workflow
## Decision Outcome
We decided to divide the system in layers because the system under 
construction does not suggest an organization by data flow or control flow. 
### Consequences
* Good: Layers provide high flexibility regarding technology selection each layer 
and enables teams to work in parallel on different layers. 
* Bad: There might be a performance penalty for each level of indirection.
## More Information
* We divided the system in three layers: UI, business logic, and data storage.
