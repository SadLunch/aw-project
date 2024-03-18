## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the categories component without affecting other parts of the application
## Considered Options
1. Include the location, banner and products within the same microfrontend
2. Create a separate microfrontend for the location, banner and products of the selected shop
## Decision Outcome
We decided to implement the location, banner and products within the same microfrontend 
### Consequences
Good:
* Easy to maintain and develop new functionalities
* Enables a more cohesive developer experience

Bad:
* Does not promote reusability of the location, banner and products components across multiple screens
* Does not enable independent updates to the location, banner and products without affecting other parts of the application
* Does not enable teams to work in paralell on different microfrontends
## More Information
* The shop microfrontend consists of components that help the user visualize the selected shop's location, banner and products
