## SpaceStock Listing Backend Services

### About this services
This is a simple backend Services to supply my other git repo which is space-stock-listng, it use a fake REST API using an incredible tool called JSON-Server. This is used for mocking and prototyping and is something that I personally use all of the time. It is useful to anyone building frontend apps with something like Angular, React, etc.

### Getting Started
To Start this Server, simply clone this repository using command line

  ```
    git clone https://github.com/ivandi1980/space-stock-listing-backend.git
  ```
or you can download the Zip file

after you download or cloning this repository, the next step is run

  ```
    npm install
  ```

### Running the server
To Running the Server simply type this command on your console

  ```
    npm run json:server
  ```

this command will run the server on port:5000 that was already setup on package.json file and if you see here is the command

  ```
    "scripts": {
      "json:server": "json-server --watch db.json --port 5000"
    },
  ```
After you running the server

  ```
    http://localhost:5000
  ```

you will get the documentation dashboard, you can diving into the documentation to see what would you get.


### Folder Structure
Here is the folder structure after you done with npm intall or after you got all the dependencies

  ```
    space-stock-listing-backend/
    |--node_modules/
    |--.gitignore
    |--db.json
    |--package-lock.json
    |--package.json
    |--README.md
  ```

### The Routes
In every REST-API world you can find many kinds of Routes that provided by the services, like

  ```
    GET, POST, PUT, DELETE, etc
  ```

but in this case, we just use METHOD GET, because this is very simple REST API.
The Routes that i provide here is

  ```
    GET http://localhost:5000 (Dashboard)
    GET http://localhost:5000/data (Fetch All Data)
    GET http://localhost:5000/data/1 (Fetch 1 Specific Data)
  ```
