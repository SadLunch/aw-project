## Context and Problem Statement
To maintain modularity and flexibility in the application's front-end architecture
## Decision Drivers
* Divide the overall system into logical building blocks
* Enable independent updates to the categories component without affecting other parts of the application
## Considered Options
1. Include the QR Code and the product scanned within the same microfrontend
2. Create a separate microfrontend for the product scanned
## Decision Outcome
We decided to implement the QR Code and the product scanned within the same microfrontend
### Consequences
Good:
* Easier for the team to maintain and develop the QR Code functionalitie

Bad:
* The QR Code team as to be aware of the product scanned functionalities
## More Information
* The QR Code microfrontend consists of components that help the user scan the product and visualize the product's information
