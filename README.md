# FoodAdvisor - API

![FoodAdvisor](../foodadvisor.png)

Welcome to FoodAdvisor, the official Strapi demo application.

## Get started

You can get started with this project locally on your machine by following the instructions below or you can [request a private instance on our website](https://strapi.io/demo).

## Prerequisites

Be sure to have the correct env variabless:

- Strapi:
  - `CLIENT_URL=<url-of-nextjs>`
  - `CLIENT_PREVIEW_SECRET=<a-random-token>`

## Start Strapi

- Run the following command in your `./foodadvisor/api` folder:

```
yarn && yarn run seed && yarn develop
```

This will install the dependencies, fill your application with data and run your server. You can run these commands separately.

<a href="https://www.heroku.com/deploy/?template=https://github.com/buzzwin/buzzwin-strapi.git">
<img src="https://assets.strapi.io/uploads/Deploy_button_heroku_b1043fc67d.png" />
</a>