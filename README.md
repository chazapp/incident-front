# Incidents Front
![tests](https://github.com/chazapp/incidents-front/actions/workflows/tests.yml/badge.svg)
[![codecov](https://codecov.io/gh/chazapp/incidents-front/branch/master/graph/badge.svg?token=IE1EZ23LZV)](https://codecov.io/gh/chazapp/incidents-front)  

This project contains the Typescript front-end client used with the
[Incidents API](https://github.com/chazapp/incidents-api) project.

It can: 
 - Login/Logout 
 - Create new Incidents via a dedicated form
 - List and search all incidents 
 - CRUD incidents
 - Dashboard with metrics

## Usage

```
$ yarn install
$ echo "REACT_APP_API_URL=http://..." >> .env
$ yarn cypress:run
$ yarn start
```

You may also run the automated Cypress test suite.

```
# Provide the login credentials in your environment:
$ echo "CYPRESS_INCIDENTS_USER=..." >> .env
$ echo "CYPRESS_INCIDENTS_PASSWORD=..." >> .env
# Run the test suite headlessly
$ yarn cypress:run
# Run the test suite in Cypress browser
$ yarn cypress:open
```
