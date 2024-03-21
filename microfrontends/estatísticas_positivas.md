## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the categories component without affecting other parts of the application
## Considered Options
1. Include all the graphics within the same microfrontend
2. Devide some of the graphics into separate microfrontends
## Decision Outcome
We decided to implement all the graphics within the same microfrontend
Good:
* Performance gains due to decreased network requests
* Easier to maintain and update
* Easier to implement

Bad:
* Doesn't promote reusability of the component across multiple screens
* Doesn't enable independent updates of the component
* Doesn't enable teams to work in paralell on different microfrontends
## More Information
* The positive statistics microfrontend consists of components that help users see the positive statistics of the butchery shop