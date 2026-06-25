# DAVe Selfservice-Portal
Urban mobility planning depends on reliable traffic data and intuitive analysis tools. DAVe (Database and Evaluation of Traffic Counts / Datenbank und Auswertung für Verkehrszählungen) is an open-source platform to manage, evaluate, and visualize traffic data. 
The software enables municipalities, transport planners, and mobility departments to analyze traffic flows, monitor long-term developments, and support data-driven infrastructure planning.

DAVe was started and opensourced by the Mobility Department of the City of Munich. This is Starwit's distribution, which is focused on easy operations.

Self-Service Portal offers functions to require counting jobs from service providers.

## About the project
This repository is one of the 5 components of the 'DAVe' application Not all five components necessarily have to be used at the same time. Following table shows DAVe's main components.

| Component        | Repository / URI                                           | Description                  |
| -----------------| -----------------------------------------------------------| -----------------------------|
| DAVe Backend     | https://github.com/starwit/dave-backend                    | Data Storage & Business Logic|
| DAVe Frontend    | https://github.com/starwit/dave-frontend                   | Analytics Frontend           |
| DAVe Admin Portal | https://github.com/starwit/dave-admin-portal              | Administration Frontend      |
| DAVe Self Service Portal | https://github.com/starwit/dave-selfservice-portal | Self-Service for data upload |
| DAVe Adapter     | https://github.com/starwit/dave-adapter                    | Connect to data platform & sensors|

The self-service portal serves as communication between the LHM and the counting service provider. Via this portal, the service provider has the ability to retrieve their counting assignments online and assign (upload) count data to these assignments. This data can then be reviewed by the LHM via the Admin Portal and released for further use. It is currently the only way to enter new count data into the system using the web interface.

## Developer Info

See [dev doc](/docs/Readme.md) for instruction for developers.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated! This edition of DAVe is published under the AGPLv3 license. See section [license](#license) for more details. All contributions will also be published under this license.

## License
Everything in this repo is licensed under AGPL 3 and the license can be found [here](LICENSE).

## Contact
For Munich's edition it@m - opensource@muenchen.de

For Starwit's edition contact info@starwit.de

