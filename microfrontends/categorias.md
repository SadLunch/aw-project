## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the categories component without affecting other parts of the application
## Considered Options
1. Include a categories component within the shops' location screen
2. Create a separate microfrontend for the categories component
## Decision Outcome
We decided to implement a separate microfrontend for the categories component 
### Consequences
Good:
* Promotes reusability of the categories component across multiple screens
* Enables independent updates to the categories without affecting other parts of the application
* Enables teams to work in paralell on different microfrontends

Bad:
* Potencial performance impact due to increased network requests and indirection
## More Information
* The categories microfrontend consists of components that help showcase the available categories of meat in the selected shop's location
