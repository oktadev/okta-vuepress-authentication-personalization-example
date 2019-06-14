# Add Authentication and Personalization to VuePress

This example VuePress application is for the blog post [Add Authentication and Personalization to VuePress](https://developer.okta.com/blog/2019/06/14/add-authentication-and-personalization-to-vuepress).

## Setup

To use this example project, you need the following:

* A recent version of [Node.js](https://nodejs.org/)
* A [free Okta Developer Account](https://developer.okta.com/signup/)

## Download and Configure the Project

1. Download or clone the project.
1. Run `npm install` at the command line from within the project folder to install dependencies.
1. Create a new **Single-Page Application** in your Okta account.
1. Copy the `docs/.vuepress/oktaConfig.js.sample` file to `docs/.vuepress/oktaConfig.js`
1. Copy the `Client ID` from your Okta application and the `Org URL` from your Okta account and update the values in the `oktaConfig.js` file.

Launch the application using the following at the command line:

```sh
npm run dev
```

Browse to `https://localhost:8080`.
