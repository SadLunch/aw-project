## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the categories component without affecting other parts of the application
## Considered Options
1. Devide the shop finding and featured products into separate microfrontends
2. Include the shop finding and featured products within the same microfrontend
## Decision Outcome
We decided to implement the shop finding and featured products within the same microfrontend
* Performance gains due to decreased network requests
* Easier to maintain and update
* Easier to implement

Bad:
* Doesn't promote reusability of the component across multiple screens
* Doesn't enable independent updates of the component
* Doesn't enable teams to work in paralell on different microfrontends
## More Information
* The shop finding and featured products microfrontend consists of components that help users find a shop and see featured products
