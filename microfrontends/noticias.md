## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the news component without affecting other parts of the application
## Considered Options
1. Include a news component within the news's screen
2. Create a separate microfrontend for the news component
## Decision Outcome
We decided to implement a separate microfrontend for the news component 
### Consequences
Good:
* Promotes reusability of the news component across multiple screens
* Enables independent updates to the news without affecting other parts of the application
* Enables teams to work in paralell on different microfrontends

Bad:
* Potencial performance impact due to increased network requests and indirection
## More Information
* The News microfrontend consists of components that showcase news related to the application's main subject
