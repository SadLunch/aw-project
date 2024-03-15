## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the map component without affecting other parts of the application
## Considered Options
1. Include a map component within the shops' location screen
2. Create a separate microfrontend for the map component
## Decision Outcome
We decided to implement a separate microfrontend for the map component 
### Consequences
Good:
* Promotes reusability of the map component across multiple screens
* Enables independent updates to the map without affecting other parts of the application
* Enables teams to work in paralell on different microfrontends

Bad:
* Potencial performance impact due to increased network requests and indirection
## More Information
* The Map microfrontend consists of a map component that helps show where the shop is located
