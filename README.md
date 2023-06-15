![Photo by Joshua Woroniecki on Unsplash](https://user-images.githubusercontent.com/2342458/204334325-7625b781-db8a-40b5-ac3c-91f2d7c8c526.png)

# Kinsta - Hello World - NuxtJS

An example of how to deploy a **NuxtJS** application on Kinsta.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

- [Start your free trial](https://kinsta.com/signup/?product_type=app-db)
- [Application Hosting](https://kinsta.com/application-hosting)
- [Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management

Kinsta automatically installs dependencies defined in your `package.json` file during the deployment process.

## Web Server Setup

### Port

Kinsta automatically sets the `PORT` environment variable. You should **not** define it yourself and you should **not** hard-code it into the application.

### Start Command

When deploying an application, Kinsta automatically creates a web process with `npm start` as the entry point. Make sure to use this command to run your server.

## Deployment Lifecycle

Whenever a deployment is initiated (through creating an application or re-deploying due to an incoming commit) the `npm build` command is run, followed by the `npm start` command.

## What is NuxtJS
NuxtJS is an open-source web development framework that allows you to build server-side rendered Vue.js applications and static sites. More information is available on the [Nuxtjs.org](https://nuxtjs.org/) website.
