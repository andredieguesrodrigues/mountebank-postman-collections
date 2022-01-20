# Mountebank Collections

## Overview

These collections were created to give some examples of the use of the Mountebank and how to better explore its features.

## Requirements

- [*Mountebank*](http://www.mbtest.org/)
- [*Postman*](https://www.postman.com/)
- [*Newman*](https://www.npmjs.com/package/newman)

## Collections

    - Eshopper.: Collection to demonstrate the use of mountebank to inject behaviour inside the stubs and keep control state the application between endpoints.
    - Proxy.: Example using proxyOnce mode to toggle redirection to mocked or real responses.
    - Repeat.: Possibility to have distinct mocked responses with the same input parameters.

## How to Run

1. Open command line and just type 'mb --allowInjection'
2. To create imposters and stubs is possible use the following ways.:
    a. Call individually each endpoint in folder "Methods" by Postman (or any software to call rest API's of your preference)
    b. Use newman to run all endpoints sequentially in automated way with this command.: npx newman run <<collection> --folder "<<folder>>"
       Example (Eshopper).: npx newman run eshopper_collection.json --folder "1. Methods"

## Contacts and Maintainers

If you have questions or suggestions, please contact the current maintainers.:

-   André Diegues Rodrigues - andrevdrodrigues@gmail.com


