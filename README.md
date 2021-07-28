## Product and Engineering Managers: Where is your software?

This GitHub repository contains the code for the Pagerduty and JFrog workshop hosted on [jfrog.awsworkshop.io](http://jfrog.awsworkshop.io). Visit [jfrog.awsworkshop.io](http://jfrog.awsworkshop.io) for the workshop instructions.

PagerDuty and JFrog provide a hands-on demonstration of how you can configure your software delivery pipeline to provide real-time updates to your product managers and engineering managers. In this workshop, you will learn about the JFrog Cloud Platform and how to leverage JFrog Pipelines, Artifactory and Xray for managing your Software Development Lifecycle (SDLC) and bring DevOps to the cloud. Then you will see how JFrog's native integration with PagerDuty provides cloud DevOps observability. With PagerDuty's DevOps dashboards, product managers and engineering managers can get real-time status on the progress of their software features and bug fixes, understand how software builds are progressing and where they are being deployed. Users can see which software is being released, where and much more!

![Pipeline](https://user-images.githubusercontent.com/6440106/127360109-1da5a406-385b-4aa6-ac95-586cd3ed163b.png)

Learning Objectives:
- Understand the roles of JFrog Pipelines, Artifactory and Xray in your software delivery life cycle (SDLC).
- Use Local, Remote and Virtual Repositories in Artifactory.
- Publish and promote your software builds.
- Scan your artifacts and builds for security vulnerabilities.
- Deploy your applications as part of your CI/CD pipeline onto an AWS EKS cluster.
- Learn how to set up a PagerDuty environment to monitor the various stages of your CI/CD pipeline in real-time.
- Understand how you can use actionable, granular information from the pipeline to respond quickly to failing or slow builds.

# Workshop App Local Development

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.7.

![pagerduty-workshop-app](https://user-images.githubusercontent.com/6440106/127370735-141fe099-e669-46b5-8bd0-a81835058bb2.png)

## Build and Run Docker Image Locally

```
$ docker build -t workshop-app . 
$ docker run -p 443:443 -p 80:80 docker.io/library/workshop-app
```

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

