# GraphQL / Apollo Server Dog API

A simple Apollo Server GraphQL API that allows users to get all dogs in a data set, and then also search to see if a certain dog exists (by looking up name)

The entire application is contained within the `index.js` file.

`package.json` is a npm package file allowing us to use npm commands (npm start, etc.) and store the versions of dependencies (such as apollo-server version).

## Install

    npm install

## Run the app

    npm start


# REST API

The REST API to the example app is described below.

## Get list of Things

### Request

`query `

    curl -i -H 'Accept: application/json' http://localhost:7000/thing/

### Response

    HTTP/1.1 200 OK
    Date: Thu, 24 Feb 2011 12:36:30 GMT
    Status: 200 OK
    Connection: close
    Content-Type: application/json
    Content-Length: 2

    []
