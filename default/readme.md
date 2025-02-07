# Edgio starter template

The starter template is the fastest way to enable the Edgio Edge Network for your website. Take a second to review the following steps to get going. 

A full guide can be located at [docs.edg.io](https://docs.edg.io). 

## Running your project

```
edgio dev
```

starts up your project. Make sure the origin domain is set up correctly to ensure content will appear. 

## Updating site config

In `edgio.config.js` make sure that the origin site domain is correct. During development this can be the existing domain, but for a full launch you will want to update that to be a subdomain in order to point the top level domain to this project. Additional details are available in the [app.layer0.co](https://app.layer0.co) cockpit.

## Updating routes

In `src/routes`, you can add routes for your site. When a match occurs, it can then have the cache rules applied to it. 

In `src/route-handler` you can configure the caching behavior of those matched paths. 

## Deploy your project

You can deploy the project at any point (even without changing items above) with a simple command 

```
edgio deploy
```

This command will provide a url to now view the site. 

## Getting help

The Edgio platform offers a lot of capabilities and possibilities. Reading the [docs](https://docs.edg.io) will help realize the full potential of the platform and your site. 

Visit our [forum](https://forum.edg.io) at any point to ask questions and get help from the Edgio team members and the community.