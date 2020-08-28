# MonoRepo

ZemoPay's Pagadoria and Contractor-Pay products repository. They are products of billet generating and payment making. With them, it is possible to issue billets with and without split of tax for beneficaries, make payments, create slips in the slips for your customers, in addition to registering the banks that wish to receive payments.

## Getting Started

Before creating a copy of this project, you must have all of the requirements below.

### Requirements

You need to install the software below.

```
Visual Studio Code (code editor).
```
> !Visual Studio Code is a code editor from Microsoft.

```
NodeJS and NPM (latest LTS version).
```
> !NodeJS and NPM are installed together.

```
DBeaver Community (or another database manager).
```
> !DBeaver is a database manager.

```
Git (commands for code versioning control).
```

> !If you are having problems or difficulty with the installation, you can search for tutorials on YouTube. Rocketseat tutorials are recommended.

### Clone Project

- Clone this repository to your machine using git commands.

```shell
$ git clone {repository URL}
```

### .env and DataBase Configuration

- To configure the .env and DataBase, contact one of the project's developers.

> !To make sure that everything is right, perform a test on an endpoint with the developer.

### Start Project

- To start the project, you see the command in the file ```package.json```.

```shell
  "dev": "nodemon --exec babel-node app.js",
  "start": "babel-node app.js"
```
