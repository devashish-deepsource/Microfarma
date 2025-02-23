[![CircleCI](https://dl.circleci.com/status-badge/img/gh/KOSASIH/Microfarma/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/KOSASIH/Microfarma/tree/main)

# Microfarma - Healthcare Microservice Supply Chain System

Microfarma is a healthcare microservice supply chain system that aims to revolutionize the pharmaceutical industry by leveraging microservices architecture and modern technologies. It is designed to streamline and optimize the process of supplying pharmaceutical products, ensuring efficient distribution and delivery of medicines to healthcare providers and patients.

## Key Features

1. **Microservice Architecture:** Microfarma follows a modular approach, where different functionalities are divided into independent microservices. This allows for scalability, flexibility, and easy maintenance of the system.

2. **Supplier Management:** The system provides comprehensive supplier management capabilities, enabling efficient collaboration and communication with pharmaceutical suppliers. It allows suppliers to register, manage their product catalogs, and track inventory levels.

3. **Inventory Management:** Microfarma includes a robust inventory management module that enables tracking and monitoring of pharmaceutical products across the supply chain. It provides real-time visibility into stock levels, expiration dates, and batch numbers, ensuring optimal inventory control.

4. **Order Processing:** The platform facilitates seamless order processing, from healthcare providers placing orders to suppliers fulfilling them. It supports order tracking, status updates, and notifications, ensuring timely and accurate delivery of pharmaceutical products.

5. **Delivery Tracking:** Microfarma incorporates a delivery tracking system that enables healthcare providers and patients to monitor the status of their orders. It integrates with logistics providers and provides real-time updates on shipment progress, enhancing transparency and customer satisfaction.

6. **Quality Control:** The system incorporates quality control mechanisms to ensure compliance with regulatory standards and safety requirements. It enables tracking and tracing of products, verification of authenticity, and monitoring of product quality throughout the supply chain.

7. **Reporting and Analytics:** Microfarma includes powerful reporting and analytics capabilities, allowing stakeholders to gain insights into key performance indicators (KPIs) and make data-driven decisions. It provides comprehensive dashboards, trend analysis, and customizable reports.

8. **Security and Privacy:** The platform prioritizes the security and privacy of sensitive healthcare data. It incorporates robust authentication and authorization mechanisms, encryption of data in transit and at rest, and compliance with industry standards, such as HIPAA and GDPR.

## Technologies Used

Microfarma leverages cutting-edge technologies and frameworks to provide a scalable and efficient healthcare microservice supply chain system. Some of the key technologies used include:

- **Microservices:** The system is built using a microservices architecture, enabling modular development, scalability, and independent deployment of services.

- **Containerization:** Docker is used to containerize the microservices, allowing for easy deployment, isolation, and scalability across different environments.

- **API Gateway:** An API gateway, such as Kong or Netflix Zuul, is utilized to provide a single entry point for accessing the microservices and enforcing security, rate limiting, and other policies.

- **Message Queue:** A message queue system like Apache Kafka or RabbitMQ is employed to ensure reliable and asynchronous communication between microservices, facilitating scalability and fault tolerance.

- **Database:** A robust and scalable database management system, such as PostgreSQL or MongoDB, is used to store and manage data across the system.

- **Frontend Framework:** A modern frontend framework like React or Angular is used to build the user interface, providing a rich and interactive experience for healthcare providers, suppliers, and other stakeholders.

- **DevOps Tools:** Continuous integration and deployment are facilitated using DevOps tools like Jenkins or GitLab CI/CD, ensuring efficient development, testing, and deployment of the system.

## Installation and Setup

Detailed installation and setup instructions for Microfarma can be found in the project's documentation. It includes steps for deploying the microservices, configuring the system, and integrating with external services, such as logistics providers and databases.

## Contributing

Contributions to Microfarma are welcome! If you would like to contribute, please follow the guidelines outlined in the project's repository, including code style, documentation standards, and the pull request process.

## License

Microfarma is released under the [MIT License](https://github.com/KOSASIH/Microfarma/blob/main/LICENSE). You are free to use, modify, and distribute the software according to the terms of the license.

## Support

For any questions, issues, or support related to Microfarma, please refer to the project's repository and open a new issue. The development team will be happy to assist you.

## Acknowledgments

Microfarma is developed by a dedicated team of healthcare and technology professionals who are passionate about improving the pharmaceutical supply chain. We would like to express our gratitude to the open-source community for their invaluable contributions and inspiration.

## System Requirements

List the minimum system requirements for running Microfarma. Include details such as the operating system, hardware specifications, and software dependencies.

## Deployment

Provide step-by-step instructions on how to deploy Microfarma in a production or development environment. Include information on configuring the microservices, setting up databases, and any additional setup required.

## Usage

Explain how to use Microfarma from the perspective of different users. Provide examples and instructions for common tasks such as placing an order, managing inventory, and generating reports.

## API Documentation

If Microfarma exposes APIs for integration with other systems, provide comprehensive documentation for the available endpoints, request/response formats, and authentication mechanisms. Consider using tools like Swagger or Postman to generate and display API documentation.

## Troubleshooting

List common issues that users may encounter while using Microfarma and provide solutions or workarounds for each problem. Include information on how to troubleshoot common errors and where to find additional support.

## Roadmap

Outline the future development plans for Microfarma. Provide information on upcoming features, enhancements, and bug fixes. This gives users and contributors insights into the project's direction and encourages collaboration.

## Changelog

Document the changes and improvements made in each release of Microfarma. Include details about bug fixes, new features, and notable enhancements. This helps users and contributors keep track of the project's evolution.

## Contributing Guidelines

Provide guidelines for contributing to the Microfarma project. Include information on how to set up a development environment, coding standards, and the process for submitting pull requests. Specify any contribution guidelines or templates to follow.

## Authors

List the names or usernames of the core development team members who have contributed significantly to the Microfarma project. Provide links to their profiles or contact information.

## Related Projects

If there are any related projects or dependencies that Microfarma relies on or integrates with, mention them in this section. Provide links to their repositories or documentation for further reference.

## Resources

Include a list of external resources such as articles, tutorials, or documentation that can help users better understand Microfarma and its underlying technologies.

Remember to update the README regularly to reflect any changes, updates, or new information about Microfarma. A well-maintained and comprehensive README can greatly benefit users, contributors, and the overall success of the project.

# Microfarma

This application was generated using JHipster 8.0.0-beta.1, you can find documentation and help at [https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1](https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1).

This is a "microservice" application intended to be part of a microservice architecture, please refer to the [Doing microservices with JHipster][] page of the documentation for more information.
This application is configured for Service Discovery and Configuration with the JHipster-Registry. On launch, it will refuse to start if it is not able to connect to the JHipster-Registry at [http://localhost:8761](http://localhost:8761). For more information, read our documentation on [Service Discovery and Configuration with the JHipster-Registry][].

## Project Structure

Node is required for generation and recommended for development. `package.json` is always generated for a better development experience with prettier, commit hooks, scripts and so on.

In the project root, JHipster generates configuration files for tools like git, prettier, eslint, husky, and others that are well known and you can find references in the web.

`/src/*` structure follows default Java structure.

- `.yo-rc.json` - Yeoman configuration file
  JHipster configuration is stored in this file at `generator-jhipster` key. You may find `generator-jhipster-*` for specific blueprints configuration.
- `.yo-resolve` (optional) - Yeoman conflict resolver
  Allows to use a specific action when conflicts are found skipping prompts for files that matches a pattern. Each line should match `[pattern] [action]` with pattern been a [Minimatch](https://github.com/isaacs/minimatch#minimatch) pattern and action been one of skip (default if ommited) or force. Lines starting with `#` are considered comments and are ignored.
- `.jhipster/*.json` - JHipster entity configuration files

- `npmw` - wrapper to use locally installed npm.
  JHipster installs Node and npm locally using the build tool by default. This wrapper makes sure npm is installed locally and uses it avoiding some differences different versions can cause. By using `./npmw` instead of the traditional `npm` you can configure a Node-less environment to develop or test your application.
- `/src/main/docker` - Docker configurations for the application and services that the application depends on

## Development

Before you can build this project, you must install and configure the following dependencies on your machine:

1. [Node.js][]: We use Node to run a development web server and build the project.
   Depending on your system, you can install Node either from source or as a pre-packaged bundle.

After installing Node, you should be able to run the following command to install development tools.
You will only need to run this command when dependencies change in [package.json](package.json).

```
npm install
```

We use npm scripts and [Angular CLI][] with [Webpack][] as our build system.

If you are using hazelcast as a cache, you will have to launch a cache server.
To start your cache server, run:

```
docker compose -f src/main/docker/hazelcast-management-center.yml up -d
```

Run the following commands in two separate terminals to create a blissful development experience where your browser
auto-refreshes when files change on your hard drive.

```
./mvnw
npm start
```

Npm is also used to manage CSS and JavaScript dependencies used in this application. You can upgrade dependencies by
specifying a newer version in [package.json](package.json). You can also run `npm update` and `npm install` to manage dependencies.
Add the `help` flag on any command to see how you can use it. For example, `npm help update`.

The `npm run` command will list all of the scripts available to run for this project.

### PWA Support

JHipster ships with PWA (Progressive Web App) support, and it's turned off by default. One of the main components of a PWA is a service worker.

The service worker initialization code is disabled by default. To enable it, uncomment the following code in `src/main/webapp/app/app.module.ts`:

```typescript
ServiceWorkerModule.register('ngsw-worker.js', { enabled: false }),
```

### Managing dependencies

For example, to add [Leaflet][] library as a runtime dependency of your application, you would run following command:

```
npm install --save --save-exact leaflet
```

To benefit from TypeScript type definitions from [DefinitelyTyped][] repository in development, you would run following command:

```
npm install --save-dev --save-exact @types/leaflet
```

Then you would import the JS and CSS files specified in library's installation instructions so that [Webpack][] knows about them:
Edit [src/main/webapp/app/app.module.ts](src/main/webapp/app/app.module.ts) file:

```
import 'leaflet/dist/leaflet.js';
```

Edit [src/main/webapp/content/scss/vendor.scss](src/main/webapp/content/scss/vendor.scss) file:

```
@import 'leaflet/dist/leaflet.css';
```

Note: There are still a few other things remaining to do for Leaflet that we won't detail here.

For further instructions on how to develop with JHipster, have a look at [Using JHipster in development][].

### Developing Microfrontend

Microservices doesn't contain every required backend feature to allow microfrontends to run alone.
You must start a pre-built gateway version or from source.

Start gateway from source:

```
cd gateway
npm run docker:db:up # start database if necessary
npm run docker:others:up # start service discovery and authentication service if necessary
npm run app:start # alias for ./(mvnw|gradlew)
```

Microfrontend's `build-watch` script is configured to watch and compile microfrontend's sources and synchronizes with gateway's frontend.
Start it using:

```
cd microfrontend
npm run docker:db:up # start database if necessary
npm run build-watch
```

It's possible to run microfrontend's frontend standalone using:

```
cd microfrontend
npm run docker:db:up # start database if necessary
npm watch # alias for `npm start` and `npm run backend:start` in parallel
```

### Using Angular CLI

You can also use [Angular CLI][] to generate some custom client code.

For example, the following command:

```
ng generate component my-component
```

will generate few files:

```
create src/main/webapp/app/my-component/my-component.component.html
create src/main/webapp/app/my-component/my-component.component.ts
update src/main/webapp/app/app.module.ts
```

### JHipster Control Center

JHipster Control Center can help you manage and control your application(s). You can start a local control center server (accessible on http://localhost:7419) with:

```
docker compose -f src/main/docker/jhipster-control-center.yml up
```

### Doing API-First development using openapi-generator-cli

[OpenAPI-Generator]() is configured for this application. You can generate API code from the `src/main/resources/swagger/api.yml` definition file by running:

```bash
./mvnw generate-sources
```

Then implements the generated delegate classes with `@Service` classes.

To edit the `api.yml` definition file, you can use a tool such as [Swagger-Editor](). Start a local instance of the swagger-editor using docker by running: `docker compose -f src/main/docker/swagger-editor.yml up -d`. The editor will then be reachable at [http://localhost:7742](http://localhost:7742).

Refer to [Doing API-First development][] for more details.

## Building for production

### Packaging as jar

To build the final jar and optimize the Microfarma application for production, run:

```
./mvnw -Pprod clean verify
```

This will concatenate and minify the client CSS and JavaScript files. It will also modify `index.html` so it references these new files.
To ensure everything worked, run:

```
java -jar target/*.jar
```

Then navigate to [http://localhost:8081](http://localhost:8081) in your browser.

Refer to [Using JHipster in production][] for more details.

### Packaging as war

To package your application as a war in order to deploy it to an application server, run:

```
./mvnw -Pprod,war clean verify
```

## Testing

To launch your application's tests, run:

```
./mvnw verify
```

### Client tests

Unit tests are run by [Jest][]. They're located in [src/test/javascript/](src/test/javascript/) and can be run with:

```
npm test
```

### Other tests

Performance tests are run by [Gatling][] and written in Scala. They're located in [src/test/java/gatling/simulations](src/test/java/gatling/simulations).

You can execute all Gatling tests with

```
./mvnw gatling:test
```

For more information, refer to the [Running tests page][].

### Code quality

Sonar is used to analyse code quality. You can start a local Sonar server (accessible on http://localhost:9001) with:

```
docker compose -f src/main/docker/sonar.yml up -d
```

Note: we have turned off forced authentication redirect for UI in [src/main/docker/sonar.yml](src/main/docker/sonar.yml) for out of the box experience while trying out SonarQube, for real use cases turn it back on.

You can run a Sonar analysis with using the [sonar-scanner](https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner) or by using the maven plugin.

Then, run a Sonar analysis:

```
./mvnw -Pprod clean verify sonar:sonar -Dsonar.login=admin -Dsonar.password=admin
```

If you need to re-run the Sonar phase, please be sure to specify at least the `initialize` phase since Sonar properties are loaded from the sonar-project.properties file.

```
./mvnw initialize sonar:sonar -Dsonar.login=admin -Dsonar.password=admin
```

Additionally, Instead of passing `sonar.password` and `sonar.login` as CLI arguments, these parameters can be configured from [sonar-project.properties](sonar-project.properties) as shown below:

```
sonar.login=admin
sonar.password=admin
```

For more information, refer to the [Code quality page][].

## Using Docker to simplify development (optional)

You can use Docker to improve your JHipster development experience. A number of docker-compose configuration are available in the [src/main/docker](src/main/docker) folder to launch required third party services.

For example, to start a postgresql database in a docker container, run:

```
docker compose -f src/main/docker/postgresql.yml up -d
```

To stop it and remove the container, run:

```
docker compose -f src/main/docker/postgresql.yml down
```

You can also fully dockerize your application and all the services that it depends on.
To achieve this, first build a docker image of your app by running:

```
npm run java:docker
```

Or build a arm64 docker image when using an arm64 processor os like MacOS with M1 processor family running:

```
npm run java:docker:arm64
```

Then run:

```
docker compose -f src/main/docker/app.yml up -d
```

When running Docker Desktop on MacOS Big Sur or later, consider enabling experimental `Use the new Virtualization framework` for better processing performance ([disk access performance is worse](https://github.com/docker/roadmap/issues/7)).

For more information refer to [Using Docker and Docker-Compose][], this page also contains information on the docker-compose sub-generator (`jhipster docker-compose`), which is able to generate docker configurations for one or several JHipster applications.

## Continuous Integration (optional)

To configure CI for your project, run the ci-cd sub-generator (`jhipster ci-cd`), this will let you generate configuration files for a number of Continuous Integration systems. Consult the [Setting up Continuous Integration][] page for more information.

[JHipster Homepage and latest documentation]: https://www.jhipster.tech
[JHipster 8.0.0-beta.1 archive]: https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1
[Doing microservices with JHipster]: https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1/microservices-architecture/
[Using JHipster in development]: https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1/development/
[Service Discovery and Configuration with the JHipster-Registry]: https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1/microservices-architecture/#jhipster-registry
[Using Docker and Docker-Compose]: https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1/docker-compose
[Using JHipster in production]: https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1/production/
[Running tests page]: https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1/running-tests/
[Code quality page]: https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1/code-quality/
[Setting up Continuous Integration]: https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1/setting-up-ci/
[Node.js]: https://nodejs.org/
[NPM]: https://www.npmjs.com/
[Webpack]: https://webpack.github.io/
[BrowserSync]: https://www.browsersync.io/
[Jest]: https://facebook.github.io/jest/
[Leaflet]: https://leafletjs.com/
[DefinitelyTyped]: https://definitelytyped.org/
[Angular CLI]: https://cli.angular.io/
[Gatling]: https://gatling.io/
[OpenAPI-Generator]: https://openapi-generator.tech
[Swagger-Editor]: https://editor.swagger.io
[Doing API-First development]: https://www.jhipster.tech/documentation-archive/v8.0.0-beta.1/doing-api-first-development/


<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/KOSASIH/Microfarma">Microfarma</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.linkedin.com/in/kosasih-81b46b5a">KOSASIH</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>
