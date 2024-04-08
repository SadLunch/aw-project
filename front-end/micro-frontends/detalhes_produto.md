## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the categories component without affecting other parts of the application
## Considered Options
1. Don't spllit the product details into multiple microfrontends
## Decision Outcome
We decided to implement the product details within the same microfrontend because we couldn't find a way to split it into a separate microfrontend and thouth that it would be better to keep it in the same microfrontend
Good:
* Performance gains due to decreased network requests
* Easier to maintain and update
* Easier to implement

Bad:
* Doesn't promote reusability of the component across multiple screens
## More Information
* The product details microfrontend consists of components that help users see the details of a product
