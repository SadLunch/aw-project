## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the product component without affecting other parts of the application
## Considered Options
1. Include a product component within the specific product screen
2. Create a separate microfrontend for the product component
## Decision Outcome
We decided to implement a separate microfrontend for the product component 
### Consequences
Good:
* Promotes reusability of the product component across multiple screens
* Enables independent updates to the specific product screen without affecting other parts of the application
* Enables teams to work in paralell on different microfrontends

Bad:
* Potencial performance impact due to increased network requests and indirection
## More Information
* The product microfrontend consists of components which provide information on the specific product (such as name,
price, location, specifics of the animal the product came from) and ways to give feedback on the product