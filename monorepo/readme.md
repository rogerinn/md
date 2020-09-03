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
Docker (latest stable version).
```
> !Docker is a container manager.

```
Postman (latest version).
```
> !Postman is a tool to test RESTful services.

```
Git (commands for code versioning control).
```

> !If you are having problems or difficulty with the installation, you can search for tutorials on YouTube.

### Clone Project

- Clone this repository to your machine using git commands.

```shell
$ git clone {repository URL}
```

### Docker and DataBase Configuration

- To configure the docker and DataBase, contact one of the project's developers.
> !To make sure that everything is right, perform a test on an endpoint with the developer.

```shell
docker-compose --build -d
```
>!Command to process the file and create the Docker images it contains.

```shell
npx sequelize db:create
```
>!Command to create the DataBase.

```shell
npx sequelize db:migrate
```
>!Command to create the tables on DataBase.

## Documentation

- Project documentation is on the links below.

### Pagadoria

https://documentation.zemopay.com.br/

### Contractor - Pay

https://contractorpay.zemopay.com.br/
