# Changelog

## 1.5.0

-   Large dependency update. Everything should be up-to-date again. React 16.4.2, Webpack 4.16.5, ESlint 5.

## 1.4.1 (2018-05-24)

-   Updated React to 16.4.0

## 1.4.0 (2018-05-23)

-   Added a basic Webpack config to support [Storybook](https://storybook.js.org/) integration.

## 1.3.0 (2018-05-23)

-   Added opt-in solution for serving a client side only version
-   Writing client build files to `build/client/static` instead of `build/client`
-   Bugfix: added missing `<!doctype html>` to the server response

## 1.2.2 (2018-05-18)

-   Updated Webpack to 4.8.3
-   Updated React and ReactDOM to 16.3.2
-   Updated all other deps to their most recent version
-   Fixed some annoyances with HMR in combination with Redux and React Router

## 1.2.1 (2018-04-17)

-   Updated Webpack to 4.6.0
-   Updated Redux to 4.0.0

## 1.2.0 (2018-04-17)

-   Added Jest

## 1.1.0 (2018-04-01)

-   Replaced ExtractTextWebpackPlugin with (now working) MiniCSSExtractPlugin
-   Added script to generate production build and made some improvements to the development script
-   Added React-Helmet
-   Improved server side rendering by using a configurable HTML component
-   Webpack updated to ^4.4.1
-   React + React-DOM updated to ^16.3.0
-   Allowed configuration of webpack stats in `config/webpack.config.js`
-   Several minor improvements, cleanups and fixes

## 1.0.0 (2018-03-15)

Initial release
