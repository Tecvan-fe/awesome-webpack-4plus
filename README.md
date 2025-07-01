# Awesome Webpack 5+ Learning Resources

> A curated list of awesome Webpack 4+ and 5+ learning resources, tutorials, tools, and articles. Contributions are welcome via [pull requests](https://github.com/Tecvan-fe/awesome-webpack-zh_cn/pulls) or [issues](https://github.com/Tecvan-fe/awesome-webpack-zh_cn/issues).

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Table of Contents

- [Getting Started](#getting-started)
- [Advanced Topics](#advanced-topics)
- [Performance Optimization](#performance-optimization)
- [Micro-frontends & Module Federation](#micro-frontends--module-federation)
- [Development Tools & Debugging](#development-tools--debugging)
- [Real-world Projects](#real-world-projects)
- [Video Tutorials](#video-tutorials)
- [Tools & Plugins](#tools--plugins)
- [Community Resources](#community-resources)
- [Books & Courses](#books--courses)

## Getting Started

### Basic Tutorials

- [Webpack Official Getting Started Guide](https://webpack.js.org/guides/getting-started/)
- [Webpack Concepts](https://webpack.js.org/concepts/)
- [A Complete Guide to Webpack 5](https://www.valentinog.com/blog/webpack/)
- [Webpack Tutorial for Beginners](https://www.freecodecamp.org/news/a-complete-webpack-tutorial-for-beginners/)
- [How to use Webpack with React: an in-depth tutorial](https://www.freecodecamp.org/news/learn-webpack-for-react-a36d4cac5060/)
- [Webpack Examples](https://github.com/webpack/webpack/tree/master/examples)
- [ruanyf/webpack-demos](https://github.com/ruanyf/webpack-demos)
- [Learn Webpack Course](https://github.com/AriaFallah/WebpackTutorial)
- [Webpack Handbook](https://survivejs.com/webpack/)

### Webpack 5 New Features

- [Webpack 5 Release Notes](https://webpack.js.org/blog/2020-10-10-webpack-5-release/)
- [Migration Guide to Webpack 5](https://webpack.js.org/migrate/5/)
- [Webpack 5 New Features and Changes](https://auth0.com/blog/webpack-5-changes-and-features/)
- [What's New in Webpack 5](https://blog.logrocket.com/webpack-5-adoption-guide-overview-new-features/)
- [Webpack 5 Complete Tutorial](https://github.com/leopord-lau/webpack5-book)
- [Webpack 5 with React and TypeScript](https://github.com/guojiongwei/webpack5-react-ts)
- [Understanding Webpack 5 Module Federation](https://module-federation.github.io/)

### Building Libraries & NPM Packages

- [Creating a Library with Webpack](https://webpack.js.org/guides/author-libraries/)
- [Let's Write a JavaScript Library in ES6 using Webpack and Babel](https://www.loginradius.com/blog/async/write-a-javascript-library-using-webpack-and-babel/)
- [Building and Publishing a Module with Webpack](https://www.robinwieruch.de/webpack-javascript-library/)
- [Modern JavaScript Library Development with Webpack](https://blog.bitsrc.io/building-a-modern-javascript-library-d0ae9b4b9e8d)

### Scaffolding Tools

- [Create React App](https://github.com/facebook/create-react-app)
- [Vue CLI](https://github.com/vuejs/vue-cli)
- [Angular CLI](https://github.com/angular/angular-cli)
- [Next.js](https://nextjs.org/docs/api-reference/next.config.js/custom-webpack-config)
- [Webpack CLI](https://github.com/webpack/webpack-cli)

---

## Advanced Topics

### Core Concepts Deep Dive

#### Tree Shaking
- [Tree Shaking Guide](https://webpack.js.org/guides/tree-shaking/)
- [Tree Shaking: A Reference Guide](https://auth0.com/blog/tree-shaking/)
- [Effective Tree Shaking](https://medium.com/@netxm/what-is-tree-shaking-de7c6be5cadd)
- [Understanding Tree Shaking in Webpack](https://blog.bitsrc.io/understanding-tree-shaking-in-webpack-4e2b07b44dd0)

#### Code Splitting & Lazy Loading
- [Code Splitting Guide](https://webpack.js.org/guides/code-splitting/)
- [Dynamic Imports in Webpack](https://webpack.js.org/guides/code-splitting/#dynamic-imports)
- [Lazy Loading Components](https://webpack.js.org/guides/lazy-loading/)
- [Advanced Code Splitting Patterns](https://hackernoon.com/the-100-correct-way-to-split-your-chunks-with-webpack-f8a9df5b7758)

#### Caching Strategies
- [Caching Guide](https://webpack.js.org/guides/caching/)
- [Webpack 5 Built-in Caching](https://webpack.js.org/configuration/cache/)
- [Long-term Caching](https://developers.google.com/web/fundamentals/performance/webpack/use-long-term-caching)
- [Cache Optimization Strategies](https://medium.com/webpack/webpack-5-cache-guide-9b4a60e4a7a2)

#### Module Federation
- [Module Federation Concepts](https://webpack.js.org/concepts/module-federation/)
- [Module Federation Examples](https://github.com/module-federation/module-federation-examples)
- [Practical Module Federation](https://github.com/webpack/webpack/tree/master/examples/module-federation)
- [Building Micro-frontends with Module Federation](https://blog.bitsrc.io/building-microfrontends-with-webpack-5-module-federation-3b97ffb22a0d)

### Custom Loaders

- [Writing a Loader](https://webpack.js.org/contribute/writing-a-loader/)
- [Loader API Documentation](https://webpack.js.org/api/loaders/)
- [Creating Custom Webpack Loaders](https://blog.bitsrc.io/creating-custom-webpack-loaders-3c0be1b0a4c2)
- [How to Write a Webpack Loader](https://www.robinwieruch.de/webpack-loader/)
- [Webpack Loader Examples](https://github.com/webpack-contrib/awesome-webpack#loaders)

### Custom Plugins

- [Writing a Plugin](https://webpack.js.org/contribute/writing-a-plugin/)
- [Plugin API Documentation](https://webpack.js.org/api/plugins/)
- [Creating Webpack Plugins](https://medium.com/js-imaginea/creating-webpack-plugins-84c21ab1dc7a)
- [Plugin Development Guide](https://survivejs.com/webpack/extending/plugins/)
- [Webpack Plugin Examples](https://github.com/webpack-contrib/awesome-webpack#webpack-plugins)

### Webpack Internals

- [Webpack's Dependency Graph](https://webpack.js.org/concepts/dependency-graph/)
- [Understanding Webpack's Runtime](https://blog.bitsrc.io/understanding-webpacks-runtime-7aa7b4e67f71)
- [How Webpack Works Under the Hood](https://www.freecodecamp.org/news/a-complete-introduction-to-webpack-development-environment/)
- [Webpack Compilation Process](https://medium.com/webpack/the-contributors-guide-to-webpack-part-1-a0410cc82ca4)
- [AST and Webpack](https://blog.bitsrc.io/understanding-ast-in-javascript-and-how-webpack-uses-it-f3d8e93b6b1c)

### Interview Questions

- [Webpack Interview Questions](https://github.com/styopdev/webpack-interview-questions)
- [Common Webpack Questions](https://blog.bitsrc.io/webpack-interview-questions-42fbc4d3b2b8)
- [Frontend Build Tools Interview Guide](https://www.frontendinterviewhandbook.com/build-tools)

---

## Performance Optimization

### Build Performance

- [Build Performance Guide](https://webpack.js.org/guides/build-performance/)
- [Speeding Up Webpack Builds](https://blog.logrocket.com/guide-performance-optimization-webpack/)
- [Webpack Performance Optimization](https://developers.google.com/web/fundamentals/performance/webpack/)
- [10x Faster Webpack Builds](https://blog.bitsrc.io/10-ways-to-speed-up-your-webpack-build-4c9c5e15b6d)

### Bundle Size Optimization

- [Bundle Analysis](https://webpack.js.org/guides/code-splitting/#bundle-analysis)
- [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer)
- [Reducing Bundle Size](https://webpack.js.org/guides/tree-shaking/)
- [Bundle Size Optimization Techniques](https://web.dev/reduce-javascript-payloads-with-code-splitting/)

### Production Optimizations

- [Production Mode](https://webpack.js.org/configuration/mode/#mode-production)
- [Production Build Optimization](https://webpack.js.org/guides/production/)
- [Minimizing Bundle Size](https://webpack.js.org/plugins/terser-webpack-plugin/)
- [Asset Optimization](https://webpack.js.org/loaders/image-webpack-loader/)

### Performance Analysis Tools

- [webpack-monitor](https://github.com/webpackmonitor/webpackmonitor)
- [speed-measure-webpack-plugin](https://github.com/stephencookdev/speed-measure-webpack-plugin)
- [webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard)
- [Webpack Bundle Analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer)

---

## Micro-frontends & Module Federation

### Module Federation Implementation

- [Module Federation Examples](https://github.com/module-federation/module-federation-examples)
- [Practical Module Federation](https://github.com/webpack/webpack/tree/master/examples/module-federation)
- [Module Federation with React](https://github.com/jackzhujie/module-federation-demo)
- [Vue.js Module Federation](https://github.com/module-federation/module-federation-examples/tree/master/vue-cli)
- [Angular Module Federation](https://github.com/module-federation/module-federation-examples/tree/master/angular)

### Micro-frontend Architecture

- [Single-SPA Framework](https://single-spa.js.org/)
- [Qiankun Micro-frontend Solution](https://qiankun.umijs.org/)
- [Micro-frontend Architecture Guide](https://micro-frontends.org/)
- [Building Micro Frontends](https://www.oreilly.com/library/view/building-micro-frontends/9781492082989/)

### Best Practices

- [Module Federation Best Practices](https://module-federation.github.io/guide/basic/host.html)
- [Micro-frontend Communication Patterns](https://martinfowler.com/articles/micro-frontends.html)
- [State Management in Micro-frontends](https://blog.bitsrc.io/state-management-in-micro-frontends-8c99d5dfe71c)

---

## Development Tools & Debugging

### Source Maps

- [Source Maps Configuration](https://webpack.js.org/configuration/devtool/)
- [Source Maps Guide](https://webpack.js.org/guides/development/#using-source-maps)
- [Debugging with Source Maps](https://blog.teamtreehouse.com/introduction-source-maps)
- [Source Map Best Practices](https://developers.google.com/web/tools/chrome-devtools/javascript/source-maps)

### Development Server

- [webpack-dev-server](https://webpack.js.org/configuration/dev-server/)
- [Hot Module Replacement](https://webpack.js.org/concepts/hot-module-replacement/)
- [webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware)
- [Development Environment Setup](https://webpack.js.org/guides/development/)

### Debugging Techniques

- [Debugging Webpack](https://webpack.js.org/contribute/debugging/)
- [Chrome DevTools for Webpack](https://developers.google.com/web/tools/chrome-devtools/webpack)
- [Webpack CLI Debug Options](https://webpack.js.org/api/cli/#debugging-options)
- [VS Code Webpack Debugging](https://code.visualstudio.com/docs/nodejs/nodejs-debugging)

### Development Workflow

- [Webpack Watch Mode](https://webpack.js.org/configuration/watch/)
- [Live Reloading](https://webpack.js.org/guides/development/#using-webpack-dev-server)
- [Error Handling](https://webpack.js.org/configuration/optimization/#optimizationemitonerrorswhilecompilation)
- [Progress Reporting](https://webpack.js.org/plugins/progress-plugin/)

---

## Real-world Projects

### React Projects

- [React + Webpack 5 Boilerplate](https://github.com/taniarascia/webpack-boilerplate)
- [React TypeScript Webpack Template](https://github.com/Microsoft/TypeScript-React-Starter)
- [Advanced React Webpack Configuration](https://github.com/facebook/create-react-app/tree/master/packages/react-scripts)
- [React SSR with Webpack](https://github.com/webpack/webpack/tree/master/examples/side-effects)

### Vue.js Projects

- [Vue CLI Webpack Config](https://cli.vuejs.org/guide/webpack.html)
- [Vue.js Webpack Template](https://github.com/vuejs-templates/webpack)
- [Vue 3 + Webpack 5 Setup](https://github.com/webpack/webpack/tree/master/examples/harmony)

### Angular Projects

- [Angular CLI Webpack](https://angular.io/guide/webpack)
- [Custom Webpack Config for Angular](https://github.com/just-jeb/angular-builders)
- [Angular Elements with Webpack](https://angular.io/guide/elements)

### Full-Stack Applications

- [MERN Stack with Webpack](https://github.com/microsoft/TypeScript-Node-Starter)
- [Express + Webpack SSR](https://github.com/webpack/webpack/tree/master/examples/server-side-rendering)
- [Webpack + GraphQL](https://github.com/webpack/webpack/tree/master/examples/graphql)

### Enterprise Examples

- [Large Scale Webpack Configuration](https://github.com/webpack/webpack/tree/master/examples/common-chunk-and-vendor-chunk)
- [Multi-Page Application](https://github.com/webpack/webpack/tree/master/examples/multiple-entry-points)
- [Webpack Federation in Production](https://github.com/module-federation/universe)

---

## Video Tutorials

### Beginner Tutorials

- [Webpack Crash Course](https://www.youtube.com/watch?v=lziuNMk_8eQ) - Traversy Media
- [Webpack 5 Tutorial](https://www.youtube.com/watch?v=X1nxTjVDYdQ) - The Net Ninja
- [Learn Webpack in 15 Minutes](https://www.youtube.com/watch?v=TzdEpgONurw) - Web Dev Simplified
- [Webpack for Beginners](https://www.youtube.com/playlist?list=PLblA84xge2_zwxh3XJqy6UVxS60YdusY8) - Colt Steele

### Advanced Tutorials

- [Webpack 5 Advanced Features](https://www.youtube.com/watch?v=p-MhcctfWKw) - Academind
- [Module Federation Deep Dive](https://www.youtube.com/watch?v=s_Fs4AXsTnA) - Jack Herrington
- [Webpack Performance Optimization](https://www.youtube.com/watch?v=y_RFOaSDL8I) - Steve Kinney
- [Custom Webpack Plugins](https://www.youtube.com/watch?v=tMC5XdJTGhQ) - Sean Larkin

### Conference Talks

- [Webpack 5: What's New](https://www.youtube.com/watch?v=3On5Z0gjf4U) - Tobias Koppers
- [Module Federation](https://www.youtube.com/watch?v=D3XYAx30CNc) - Zack Jackson
- [The Future of Bundlers](https://www.youtube.com/watch?v=_-7H5LqsEH4) - Evan You

---

## Tools & Plugins

### Essential Plugins

- [html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin) - Generate HTML files
- [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) - Extract CSS
- [clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) - Clean output directory
- [copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) - Copy files
- [terser-webpack-plugin](https://github.com/webpack-contrib/terser-webpack-plugin) - JavaScript minification
- [optimize-css-assets-webpack-plugin](https://github.com/NMFR/optimize-css-assets-webpack-plugin) - CSS optimization
- [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) - Bundle analysis

### Essential Loaders

- [babel-loader](https://github.com/babel/babel-loader) - Transpile ES6+
- [css-loader](https://github.com/webpack-contrib/css-loader) - Load CSS
- [style-loader](https://github.com/webpack-contrib/style-loader) - Inject CSS
- [sass-loader](https://github.com/webpack-contrib/sass-loader) - Compile Sass
- [postcss-loader](https://github.com/webpack-contrib/postcss-loader) - Process CSS with PostCSS
- [file-loader](https://github.com/webpack-contrib/file-loader) - Load files
- [url-loader](https://github.com/webpack-contrib/url-loader) - Load files as data URLs
- [ts-loader](https://github.com/TypeStrong/ts-loader) - TypeScript loader

### Development Tools

- [webpack-dev-server](https://github.com/webpack/webpack-dev-server) - Development server
- [webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) - HMR middleware
- [webpack-merge](https://github.com/survivejs/webpack-merge) - Merge configurations
- [cross-env](https://github.com/kentcdodds/cross-env) - Cross-platform environment variables
- [dotenv-webpack](https://github.com/mrsteele/dotenv-webpack) - Environment variables from .env

### Analysis & Optimization Tools

- [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) - Interactive bundle analyzer
- [speed-measure-webpack-plugin](https://github.com/stephencookdev/speed-measure-webpack-plugin) - Measure build speed
- [duplicate-package-checker-webpack-plugin](https://github.com/darrenscerri/duplicate-package-checker-webpack-plugin) - Check for duplicates
- [circular-dependency-plugin](https://github.com/aackerman/circular-dependency-plugin) - Detect circular dependencies

---

## Community Resources

### Official Resources

- [Webpack Official Website](https://webpack.js.org/)
- [Webpack Documentation](https://webpack.js.org/concepts/)
- [Webpack GitHub Repository](https://github.com/webpack/webpack)
- [Webpack CLI](https://github.com/webpack/webpack-cli)
- [Webpack Dev Server](https://github.com/webpack/webpack-dev-server)

### Community

- [Webpack Twitter](https://twitter.com/webpack)
- [Webpack Discord](https://discord.gg/webpack)
- [Stack Overflow - Webpack](https://stackoverflow.com/questions/tagged/webpack)
- [Reddit - r/webpack](https://www.reddit.com/r/webpack/)
- [Webpack Discussions](https://github.com/webpack/webpack/discussions)

### Blogs & Articles

- [Webpack Medium Publication](https://medium.com/webpack)
- [SurviveJS Webpack Book](https://survivejs.com/webpack/)
- [Webpack Contributors Blog](https://webpack.js.org/contribute/)
- [awesome-webpack](https://github.com/webpack-contrib/awesome-webpack) - Community collection

### Newsletters & Updates

- [Webpack Newsletter](https://webpack.js.org/newsletter/)
- [This Week in Webpack](https://medium.com/webpack)
- [JavaScript Weekly](https://javascriptweekly.com/) - General JS news including Webpack

---

## Books & Courses

### Books

- [SurviveJS - Webpack](https://survivejs.com/webpack/) - Free online book
- [Webpack: The Definitive Guide](https://www.oreilly.com/library/view/webpack-the-definitive/9781492051923/)
- [Learning Webpack](https://www.packtpub.com/product/learning-webpack/9781786462329)
- [Modern JavaScript Tools & Skills](https://wesbos.com/javascript) - Includes Webpack

### Online Courses

- [Webpack Academy](https://webpack.academy/) - Official Webpack courses
- [Webpack Course on Udemy](https://www.udemy.com/course/webpack-from-beginner-to-advanced/)
- [Frontend Masters - Webpack Workshop](https://frontendmasters.com/workshops/webpack/)
- [Pluralsight Webpack Course](https://www.pluralsight.com/courses/webpack-fundamentals)

### Certification & Training

- [Webpack Certification Program](https://webpack.academy/certification)
- [Linux Foundation Training](https://training.linuxfoundation.org/training/introduction-to-open-source-development-git-and-linux/)

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.