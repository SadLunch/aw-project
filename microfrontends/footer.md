## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Ensure consistent navigation across all screens
* Enable independent updates to the footer component without affecting other parts of the application
## Considered Options
1. Include a footer component within each individual navigable screen
2. Create a separate microfrontend for the footer component
## Decision Outcome
We decided to implement a separate microfrontend for the footer component 
### Consequences
Good:
* Promotes reusability of the footer component across multiple screens
* Enables independent updates to the footer without affecting other parts of the application
* Enables teams to work in paralell on different microfrontends

Bad:
* Potencial performance impact due to increased network requests and indirection
## More Information
* The Footer microfrontend consists of elements to assist navigation between the main screens of the application
* It provides consistent navigation assistance across the application while maintaining modularity in the front-end architecture
