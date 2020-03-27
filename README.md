# Emergency Site Template

A boilerplate for emergency information websites. (WIP) ([Demo Site](https://emergency-site.dev))

In case of emergency, many organizations need a quick way to publish critical information. Existing CMS websites are often unable to handle sudden spikes in traffic, and local infrastructure might be damaged, leaving people with poor mobile connections.

This project aims to enable developers to quickly publish a simple website that can withstand large amounts of traffic and will work even under extreme conditions. It is built on the [rule of least power](https://en.wikipedia.org/wiki/Rule_of_least_power), using simple technologies for maximum resilience.

## Features

* Static Files generated by [Eleventy](https://11ty.dev)
* Optimized for first Roundtrip (> 14KB)
* Basic Styling for Accessibility
* One Request, Inlined CSS
* [Netlify CMS](https://www.netlifycms.org/) for collaborative Content Editing
* Offline Support with Service Worker

## Getting Started

To publish a website with this template, there are two options, depending on your technical skillset. Choose which one describes you best:

* [I'm not a developer](https://github.com/maxboeck/emergency-site/blob/master/src/posts/2020-03-20-getting-started.md#no-code-setup), I just want to set up a website
* [I have basic knowledge](https://github.com/maxboeck/emergency-site/blob/master/src/posts/2020-03-20-getting-started.md#advanced-setup) of how to use `npm` and the command line 

Read the [Getting Started Docs](https://github.com/maxboeck/emergency-site/blob/master/src/posts/2020-03-20-getting-started.md)

## One-Click Deployment

The easiest way to go live is by forking this repo and deploying it to Netlify.  
You can do that by clicking this button:  

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/maxboeck/emergency-site) 

To customize the site, edit `src/data/meta.json` with your details, and replace the markdown files in `src/posts` with your content.

## Local Development

To run this locally, you need to install [Node](https://nodejs.org/en/) first.  
You can run these on the command line in the root of your project:

* `npm start`: starts development server
* `npm run build`: generates a production build
* `npm run debug`: runs eleventy with debug output

To customize the site, edit `src/data/meta.js` with your details, or set the corresponding [environment variables](https://github.com/maxboeck/emergency-site/blob/master/src/posts/2020-03-20-getting-started.md#configure-your-site) in a new `.env` file in the root folder of the project.
