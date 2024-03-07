## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Ensure consistent branding and/or navigation across all screens
* Enable independent updates to the header component without affecting other parts of the application
## Considered Options
1. Include a header component within each individual screen
2. Create a separate microfrontend for the header component
## Decision Outcome
We decided to implement a separate microfrontend for the header component 
### Consequences
Good:
* Promotes reusability of the header component across multiple screens
* Enables independent updates to the header without affecting other parts of the application
* Enables teams to work in paralell on different microfrontends

Bad:
* Potencial performance impact due to increased network requests and indirection
## More Information
* The Header microfrontend consists of elements such as the application's name, navigation icons, and/or logo.
