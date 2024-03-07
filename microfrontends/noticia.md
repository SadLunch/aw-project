## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the specific news component with affecting other parts of the application
## Considered Options
1. Include a specific news component within the news's screen
2. Create a separate microfrontend for the specific news component
## Decision Outcome
We decided to implement a separate microfrontend for the specific news component 
### Consequences
Good:
* Promotes reusability of the specific news component across multiple screens
* Enables independent updates to the specific news without affecting other parts of the application
* Enables teams to work in paralell on different microfrontends

Bad:
* Potencial performance impact due to increased network requests and indirection
## More Information
* The Specific News microfrontend consists of components that showcase a singular News article
