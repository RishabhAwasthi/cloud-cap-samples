# cloud-cap-samples

This is a monorepository for sample projects on Cloud Application Programming Model (CAP).

## Description

This repository provides a list of samples and reusable packages created based on [CAP](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/00823f91779d4d42aa29a498e0535cdf.html?q=cloud%20application%20programming%20model).
The SAP Cloud Application Programming Model enables you to quickly create business applications by allowing you to focus on your domain logic. It offers a consistent end-to-end programming model that includes languages, libraries and APIs tailored for full-stack development on SAP Cloud Platform.

The samples provided can be run in a local setup on sqlite db. 

#### Samples:
* [bookshop](./packages/bookshop) - Showcases different services serving the same set of data entities from a sqlite database. The services match different use cases visualized in corresponding Fiori apps.
* [bookstore](./packages/bookstore) - A variant of the bookshop application, built in a modular fashion on top of products-service and common reuse packages.
* [common-contacts](./packages/common-contacts) -  A reuse package with common domain models and services for contacts-related data.
* [common-currencies](./packages/common-currencies) - A reuse package providing common domain models and services for currencies-related data.
* [media-server](./packages/media-server) - A reuse service to manage and serve media content on behalf of other services and apps.
* [orders-service](./packages/orders-service) - A reuse package providing domain models and services to submit and manage purchase orders.
* [products-service](./packages/products-service) - A reuse package providing domain models and services to manage product catalogs.
* [reviews-service](./packages/reviews-service) - A reuse service providing generic means to add reviews and ratings to target objects, e.g. products.
* [users-service](./packages/users-service) - A reuse service for users-related functions, like registration, user profile mgmt, etc.


## Requirements
* [Node.js](https://nodejs.org/en/) v8 or higher
* [git](https://git-scm.com) 
* [sqlite](https://www.sqlite.org/download.html) (Windows only; pre-installed on Mac/Linux)

#### Optional (if you want to import the code into an editor)
* [VS Code](https://code.visualstudio.com) 
* [Add CDS extension to VS](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/be944d6d51f343f6b3f53c29c44ff00a.html)

## Download and Installation

#### Clone and build the application
`git clone https://github.wdf.sap.corp/staging-for-SAP-samples-public/cloud-cap-samples.git`

`cd samples`

`npm install`

#### Run the samples

`npm run <sample name>`

eg: `npm run bookshop`

#### Test the application

Open these links in your browser:

* <http://localhost:4004/fiori.html> &ndash; Fiori Launchpad sandbox
* <http://localhost:4004/> &ndash; generic index page

## Limitations

None

## Known Issues

None 

## How to obtain support

In case you find a bug, or you need additional support, please open an issue [here](https://github.wdf.sap.corp/staging-for-SAP-samples-public/cloud-cap-samples/issues) in GitHub.

## Contributing

In case you find a would like to contribute, please create a pull request [here](https://github.wdf.sap.corp/staging-for-SAP-samples-public/cloud-cap-samples/pulls) in GitHub.

## To-Do (upcoming changes)

None

## License

Copyright (c) 2019 SAP SE or an SAP affiliate company. All rights reserved. This file is licensed under SAP Sample Code License Agreement, except as noted otherwise in the [LICENSE](/LICENSE) file.
