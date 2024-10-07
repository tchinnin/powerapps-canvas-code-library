# Canvas Code Gallery

The Canvas Code Gallery is a Power Apps that you can deploy to your environment, that serves as a Front-End to this Repository pieces of Canvas Code.

The objective is for your makers and developers to have an easy access to all code snippets this repo contains, for them to copy in their Power Apps Studio.

You can find the latest version of the solution to download [HERE](https://github.com/tchinnin/powerapps-canvas-code-library/releases)

> [!WARNING]  
> This is a **PREMIUM** Application as it is using a Custom Connector to get GitHub Public content.

## Github as a datasource

This Power Apps has no database, it is using this repo as a Datasource.

As this is a public Repository, no authentication is needed to access its content. I created a `GitHub Public Content` custom connector to access this content with no authentication.

I maintain te [yaml-snippets.json](/canvas-code-gallery/datasources/yaml-snippets.json) file that lists all validated code-snippet in this repo for them to be available in the Canvas Code Gallery App.