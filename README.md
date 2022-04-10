> mkdir scratch

> npm init -y

> ls
> package.json

> npm install

# Contains vast majority of functions, classes, etc, that we need from Nest

@nestjs/common@7.6.17

@nestjs/core@7.6.17

# Lets Nest use Express JS for handling HTTP requests. This is an express adapter

@nestjs/platform-express@7.6.17

# Helps make decorators work.

reflect-metadata@0.1.13

typescript@4.3.2

1. Install deps
2. Setup Typescript compiler settings. see tsconfig.json
3. Create a Nest module and controller
4. Start the app!

# Request/Response and tools inside server

1. **Pipe** - Validate data contained in the request 2.**Guard** - Make sure the user is authenticated
2. **Controller** - Route the request to a particular function
3. **Service** - Run some business logic
4. **Repository** - Access a database

# Parts of Nest

1. **Controllers** - handles incoming requests(required)
2. **Services** - handles data access and business logic
3. **Modules** - groups together code(required)
4. **Pipes** - validates incoming data
5. **Filter** - handles errors that occur during request handling
6. **Guards** - handles authentication
7. **Interceptors** - add extra logic to incoming requests or outgoing responses
8. **Repositories** - handles data stored in DB
