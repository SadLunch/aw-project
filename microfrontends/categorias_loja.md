## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the categories component without affecting other parts of the application
## Considered Options
1. Include a categories component within the shops location screen
2. Create a separate microfrontend for the loaction component
## Decision Outcome
We decided to implement the location, banner and products within the same microfrontend
### Consequences
Good:
* Performance gains due to decreased network requests and indirection

Bad:
* Doesn't promote reusability of the categories component across multiple screens
* Doesn't enable independent updates to the categories without affecting other parts of the application
* Doesn't enable teams to work in paralell on different microfrontends
## More Information
* The categories microfrontend consists of components that help showcase the available categories of meat in the selected shop's location
