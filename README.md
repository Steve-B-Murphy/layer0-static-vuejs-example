## Vue with Layer0

This example is built with Vue.js to demonstrate the use and configuration of Layer0 serving a client-side-rendered application. We utilize the caching and speed optimizations provided by Layer0 to serve static resources that are rendered on the client.

## Demo

https://layer0-docs-layer0-static-vuejs-example-default.layer0.link

## Try It Now

[![Deploy with Layer0](https://a.storyblok.com/f/117912/x/e4e996094a/frame-1.svg)](https://app.layer0.co/deploy?repo=https://github.com/layer0-docs/layer0-static-vuejs-example)

## Getting Started

### Clone This Repo

Use `git clone https://github.com/layer0-docs/static-vuejs-example.git` to get the files within this repository onto your local machine.

### Install dependencies

On the command line, in the project root directory, run the following command:

```bash
npm install
```

### Run the Vue app locally on Layer0

Run the Vue app with the command:

```bash
npm run layer0:dev
```

Load the site: http://127.0.0.1:3000

### Testing production build locally with Layer0

You can do a production build of your app and test it locally using:

```bash
layer0 build && layer0 run --production
```

Setting --production runs your app exactly as it will be uploaded to the Layer0 cloud using serverless-offline.

## Deploying to Layer0

Deploying requires an account on Layer0. [Sign up here for free](https://app.layer0.co/signup). Once you have an account, you can deploy to Layer0 by running the following in the root folder of your project:

```bash
layer0 deploy
```

See [deploying](https://docs.layer0.co/guides/deploying) for more information.
