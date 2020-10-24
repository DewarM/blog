<p align="center">
  <a href="https://www.gatsbyjs.com">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Mungo Dewar Blog/Articles
</h1>

Kicked off from https://github.com/gatsbyjs/gatsby-starter-blog

_Have another more specific idea? You may want to check out our vibrant collection of [official and community-created starters](https://www.gatsbyjs.com/docs/gatsby-starters/)._

## 🚀 Developing

```shell
gatsby develop
```

Now running at `http://localhost:8000`

## Deploys

[![Netlify Status](https://api.netlify.com/api/v1/badges/db791d7b-0d9b-425b-8f2a-1a520b068fb8/deploy-status)](https://app.netlify.com/sites/wonderful-euclid-55e127/deploys)

## [Path Prefix](https://www.gatsbyjs.com/docs/path-prefix/)

As the blog is hosted under /blog to simulate a "prod" like environment path prefixing is required.

Use the following commands to check that things are working as expected. The pathPrefix is defined in `gatsby-config.js`.

```shell
gatsby build --prefix-paths
```

```shell
gatsby serve --prefix-paths
```
