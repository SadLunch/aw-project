## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Provide overall structure and layout of the application
* Enable independent updates to the shell component without affecting other parts of the application
## Considered Options
1. Establish a shell component as each individual screen's background
2. Create a separate microfrontend for the shell component
## Decision Outcome
We decided to implement a separate microfrontend for the shell component 
### Consequences
Good:
* Promotes reusability of the shell component across all screens
* Enables independent updates to the shell without affecting other parts of the application
* Enables teams to work in paralell on different microfrontends

Bad:
* Potencial performance impact due to increased network requests and indirection
## More Information
* The Shell microfrontend is the background of the application, where all the other components will be laid out
