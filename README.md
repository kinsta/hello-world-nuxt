![Photo by Joshua Woroniecki on Unsplash](https://user-images.githubusercontent.com/2342458/204334325-7625b781-db8a-40b5-ac3c-91f2d7c8c526.png)

# Kinsta - Hello World - NuxtJS

An example of how to deploy a **NuxtJS** application on Kinsta.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

Get started for free, the first $20 is on us!

[Application Hosting](https://kinsta.com/application-hosting)

[Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management

During the deployment process, Kinsta will automatically install dependencies defined in your `package.json` file.

## Web Server Setup

### Port

Kinsta automatically sets the `PORT` environment variable. You should **not** define it yourself and you should **not** hard-code it into the application.

### Start Command

When deploying an application Kinsta will automatically create a web process with `npm start` as the entry point. Make sure to use this command to run your server.

## Deployment Lifecycle

Whenever a deployment is initiated (through creating an application or re-deploying due to an incoming commit) the `npm build` command is run, followed by the `npm start` command.

## What is NuxtJS
**NuxtJS** is shipped with plenty of features to boost developer productivity and the end user experience.

### Key Features
- **Zero Configuration** - Start coding your app right away, Nuxt takes care of the rest.
- **File-system Routing** - Automatic routing and code-splitting for every page.
- **Rendering Modes** - Switch between static-site generation or on-demand server rendering.
- **Data Fetching** - Fetch your content from any source in your Vue components, SSR ready.
- **Strong Conventions** - Efficient teamwork with a strong directory structure and conventions.
- **SEO Friendly** - Meta tag management and faster time-to-content for great indexing.
- **Components Auto-import** - Use your components, Nuxt will import them with smart code-splitting.
- **Modules Ecosystem** - Extend your app with 160+ Nuxt modules and create your own.

More info on the [Nuxtjs.org](https://nuxtjs.org/) website.
