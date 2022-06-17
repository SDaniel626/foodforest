# Foodforest

# Installation

## Docker compose

Run `docker-compose up` to start the *angular* frontend server, *express* backend server, *mysql* database, and *phpmyadmin* admin interface. 

Or you can run the services separatelly without docker-compose.
 - Start the frontend server: `npm run start`
 - Start the backend server: `npm run backend`
 - Make sure to import the [database dump](./dbdump/dbdump.sql)

You can access the development server at [http://localhost:4200](http://localhost:4200). The backend API is listening on port [3000](http://localhost:300).
If you are using docker compose you can access phpMyAdmin at [http://localhost:8080](http://localhost:8080).(Credentials: root:root)

# Featues

## Authentication 

The frontend and the backend are achieved  by using [JWT tokens](https://jwt.io/).

Regular users can make read operations throug the API, and make orders. 

Admin user can delete and create other users.
They can also create, delete or modify foods, partners and couriers.

Regural user cannot access ceartain frontend pages, and ceartain API features.

## Test credencials
  admin@foodforest.com:password
  nonAdminUser@foodforest.com:password
  user@foodforest.com:password
 
