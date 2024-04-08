## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the categories component without affecting other parts of the application
## Considered Options
1. Don't split the alert into multiple microfrontends
## Decision Outcome
We decided to implement the alert within the same microfrontend because we couldn't find a way to split it into a separate microfrontend and thouth that it would be better to keep it in the same microfrontend
### Consequences
Good:
* Performance gains due to decreased network requests
* Easier to maintain and update
* Easier to implement
* Promotes reusability of the component across multiple screens

Bad:
* We coundn't find a bad thing to ding this with this approach
## More Information
* The alert microfrontend alerts the user of important information
