# .Net Core 2.2 test REST API dockerized

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

** [.NET Core 2.2] **
** [Docker] **

## Deployment

*Steps to set the app in your docker container:*

1. Place your .Net Core app inside your container:

```
docker build -t mytestapi . 
```

2. Execute the app with the following command:

```
docker run -d -p 8080:80 --name mytestapi mytestapi               

```

## Test

* To test the API, you can simply access to http://localhost:8080/api/values in your host machine.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Author

This project has been built around the official .NET and Docker examples.
It just have a few adjustments to expose the WebAPI properly.


*Adolfo Rodriguez*


