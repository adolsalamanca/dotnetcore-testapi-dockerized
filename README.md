# .Net Core 2.2 test REST API dockerized

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
.Net Core 2.2 SDK
Docker
```

### Installing

A step by step series of examples that tell you how to get a development env running

Simply build the .Net Core app inside your container

```
docker build -t mytestapi . 
```

Afterwards, run the app expo

```
docker build -t mytestapi . 
```

```

## Deployment

Simply build the .Net Core app inside your container

```
docker build -t mytestapi . 
```

Afterwards, start the app in your container with the following command

```
docker run -d -p 8080:80 --name mytestapi mytestapi               

```

## Test

* To test the API, you can simply access to http://localhost:8080/api/values in your host machine.

## Built With

* [.NET Core 2.2]
* [Docker]

## Authors

This project has been built aroun the official .NET and Docker examples with a few changes to expose the WebAPI properly.
* **Adolfo Rodriguez**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


