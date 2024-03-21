## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the categories component without affecting other parts of the application
## Considered Options
1. Devide the login, register and forgot password into separate microfrontends
2. Include the login, register and forgot password within the same microfrontend
## Decision Outcome
We decided to implement the login, register and forgot password within the same microfrontend
Good:
* Performance gains due to decreased network requests
* Easier to maintain and update
* Easier to implement

Bad:
* Doesn't promote reusability of the component across multiple screens
* Doesn't enable independent updates of the component
* Doesn't enable teams to work in paralell on different microfrontends
## More Information
* The login, register and forgot password microfrontend consists of components that help users login, register and recover their password
