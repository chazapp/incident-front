# Incidents Front
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
