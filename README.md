# customer-postman

This [readme document](https://mylifedigital.readme.io/docs/postman-collections) thoroughly explains how to import Postman collections and provides a detailed explanation of the sequence for making requests.

## Installing

1. Import the collections in the collections directory
2. Import the environments in the environments directory
3. Set the environment variables like client id, client secret and the value of `app-id` to any appId you want to use based on environment

## Usage

- You will need to run Get DG CPM JWT request in auth0 folder before using one of the DG CPM API calls.
- The Auth0 call automatically saves the JWT in a variable (see the `Tests` tab of the call).
- This variable can be used in the DG CPM API calls as a Bearer Token header.
