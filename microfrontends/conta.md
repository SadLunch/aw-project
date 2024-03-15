## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the account component without affecting other parts of the application
## Considered Options
1. Include an account component within the users' panel screen
2. Create a separate microfrontend for the account component
## Decision Outcome
We decided to implement a separate microfrontend for the account component 
### Consequences
Good:
* Promotes reusability of the account component across multiple screens
* Enables independent updates to the user panel without affecting other parts of the application
* Enables teams to work in paralell on different microfrontends

Bad:
* Potencial performance impact due to increased network requests and indirection
## More Information
* The account microfrontend consists of components which provide help to the users to manage their account preferences and information