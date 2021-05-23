# Awesome Webpack4+ 优秀学习资源

> 搜罗 Webpack 4 or 5 好文章，投稿请到此[issue](https://github.com/Tecvan-fe/awesome-webpack-zh_cn/issues/1)里提交文章，或者直接发pull request。
> 也欢迎关注公众号【Tecvan】了解更多 Webpack 好文。

## :mortar_board: 基础入门

### :closed_book: 使用 Webpack 开发 Web 应用

- [介绍 | Webpack 中文指南](https://zhaoda.net/webpack-handbook/index.html): 比较基础比较细的入门教程，很适合初学者
- [2020年了,再不会webpack敲得代码就不香了(近万字实战)](https://juejin.cn/post/6844904031240863758#heading-0): 掘金 3000 赞，非常详尽的应用指南，特别是最后性能优化那一块有很强的实践指导意义
- [webpack4 的30个步骤打造优化到极致的 react 开发环境，如约而至](https://juejin.cn/post/6844903862898262024#heading-0): 介绍 Webpack - React 开发环境搭建的方方面面，建议读者按图索骥
- [How to use Webpack with React: an in-depth tutorial](https://www.freecodecamp.org/news/learn-webpack-for-react-a36d4cac5060/)
- [webpack-contrib/awesome-webpack](https://github.com/webpack-contrib/awesome-webpack)
- [petehunt/webpack-howto](https://github.com/petehunt/webpack-howto/blob/master/README-zh.md)
- [Webpack 初学者教学课程 Part 1 - Webpack 简介](https://github.com/AriaFallah/WebpackTutorial/tree/master/zh-cn/part1)
- [A mostly complete guide to webpack 5 \(2020\)](https://www.valentinog.com/blog/webpack/)
- [Webpack Examples](https://github.com/webpack/webpack/tree/master/examples)： Webpack 官方提供的示例，涵盖大多数特性的用法
- [ruanyf/webpack-demos](https://github.com/ruanyf/webpack-demos): 阮一峰老师的 Webpack 入门示例


### :closed_book: 使用 Webpack 编写 npm 包

- [Let's Write a JavaScript Library in ES6 using Webpack and Babel](https://www.loginradius.com/blog/async/write-a-javascript-library-using-webpack-and-babel/)
- [现代前端库开发指南系列\(二\):使用 webpack 构建一个库](https://juejin.cn/post/6844904021291958286)
- [[译] 基于 Webpack 和 ES6 打造 JavaScript 类库](https://github.com/cssmagic/blog/issues/56)

### :closed_book: 使用脚手架

- [facebook/create-react-app](https://github.com/facebook/create-react-app): 快速创建 React 应用脚手架工具
- [vuejs/vue-cli](https://github.com/vuejs/vue-cli): 快速创建 Vue 应用脚手架工具
- [tjx666/awesome-chrome-extension-boilerplate](https://github.com/tjx666/awesome-chrome-extension-boilerplate) : 基于 React \& TypeScript \& Webpack 的 Chrome 扩展开发模板

<hr />

## :mortar_board: 进阶

### :closed_book: 高级特性

- Tree Shaking
  - [Webpack 4 Tree Shaking 终极优化指南](https://juejin.cn/post/6844903998634328072)
  - [Tree-Shaking性能优化实践 - 原理篇](https://juejin.cn/post/6844903544756109319)
  - [Tree-Shaking性能优化实践 - 实践篇](https://juejin.cn/post/6844903544760336398)
- 缓存
  - [Webpack5 内置缓存方案探索](https://juejin.cn/post/6847902218570432520)
- Module Federation
  - [webpack 5 ModuleFederationPlugin vue 项目初体验](https://juejin.cn/post/6883408771322740743)

### :closed_book: 如何编写 Loader

- [✏️ loader知识分享](https://juejin.cn/post/6950092728919130126): 展开讲解了 loader 的应用、种类、原理、执行方式等内容，质量很高
- [【Webpack进阶】Loader深入解析](https://zhuanlan.zhihu.com/p/360421184): 虽然阅读量跟赞都不多，但内容详尽，值得看一看
- [手把手教你撸一个 Webpack Loader](https://juejin.cn/post/6844903555673882632)
- [如何开发一个 Webpack Loader \( 一 \)](https://github.com/joeyguo/blog/issues/4)

### :closed_book: 如何编写 Plugin

- [Webpack 案例 -- vue-loader 原理分析](https://juejin.cn/post/6937125495439900685): 结合 vue-loader ，实例分析如何编写 Webpack 插件，特别分析了 vue-loader 如何解析一份 SFC 中的三种内容；如何复用 Webpack 配置中的其它 Loader

- [如何写一个webpack插件（一）](https://github.com/lcxfs1991/blog/issues/1)

### :closed_book: 实现原理

- [[万字总结] 一文吃透 Webpack 核心原理](https://mp.weixin.qq.com/s/SbJNbSVzSPSKBe2YStn2Zw)
- [理解webpack原理，手写一个100行的webpack](https://zhuanlan.zhihu.com/p/58151131)
- [Webpack HMR 原理解析](https://zhuanlan.zhihu.com/p/30669007) : 知乎高赞，非常详细的 Hot Module Replace 原理分析文档
- [AST 与前端工程化实战](https://mp.weixin.qq.com/s/2ACQ0KwdB0ph3sqj2iK-uA)

### :closed_book: 面试

- [「吐血整理」再来一打Webpack面试题](https://juejin.cn/post/6844904094281236487#heading-0): 掘金高赞，以面试题视角概要解释 Webpack 中的各个知识点
- [Webpack interview questions](https://github.com/styopdev/webpack-interview-questions)
- [webpack 中那些最易混淆的 5 个知识点](https://juejin.cn/post/6844904007362674701): 讲解 Webpack 一些常用但容易被忽视的配置项，对面试和日常应用都很有启发

### :closed_book: 系列连载

- [深入浅出 Webpack](https://webpack.wuhaolin.cn/): 应该是国内最详尽的 Webpack 书籍，从入门到应用，再到原理、工具都有介绍，非常值得入手
- [Webpack 5 知识体系](https://gitmind.cn/app/doc/fac1c196e29b8f9052239f16cff7d4c7): 一份拆解 Webpack 核心原理、架构、编译流程、loader、插件的在线知识图谱
- [随笔列表第6页 - 书生小龙 - 博客园](https://www.cnblogs.com/QH-Jimmy/default.html?page=6): 一系列 Webpack 源码分析文章，每篇文章都针对源码某一个特别小的点展开来讲
- [Webpack Book from SurviveJS](https://survivejs.com/webpack/foreword/) : 一本深入浅出 Webpack 应用、原理、工具等主题的在线书籍
- [史上最走心webpack4.0中级教程--配置之外你应该知道的事](https://www.cnblogs.com/dashnowords/p/9572755.html)
- [范文杰](https://www.zhihu.com/people/tec-van/posts) - 源码解析系列
  - [[万字总结] 一文吃透 Webpack 核心原理](https://mp.weixin.qq.com/s/SbJNbSVzSPSKBe2YStn2Zw)
  - [[源码解读] Webpack 插件架构深度讲解](https://mp.weixin.qq.com/s/tXkGx6Ckt9ucT2o8tNM-8w)
  - [十分钟精进 Webpack：module.issuer 属性详解](https://mp.weixin.qq.com/s/QkXFOHNpL0PRQtCcWIaX-g)
  - [有点难的 webpack 知识点：Dependency Graph 深度解析](https://mp.weixin.qq.com/s/kr73Epnn6wAx9DH7KRVUaA)
  - [有点难的知识点： Webpack Chunk 分包规则详解](https://mp.weixin.qq.com/s/dFrRY_ntUwmIOXzs8TYcFQ)
  - [分享几个 Webpack 实用分析工具](https://mp.weixin.qq.com/s/A0udBhvNoA0o-kX1B0rt9A)
  - [Webpack 原理系列六： 彻底理解 Webpack 运行时](https://mp.weixin.qq.com/s/nkBvbwpzeb0fzG02HXta8A)
- [刘小夕](https://juejin.cn/user/3368559358523944) - 带你深度解锁 Webpack 系列
  - [带你深度解锁Webpack系列\(基础篇\)](https://juejin.cn/post/6844904079219490830)
  - [带你深度解锁Webpack系列\(进阶篇\)](https://juejin.cn/post/6844904084927938567)
  - [带你深度解锁Webpack系列\(优化篇\)](https://juejin.cn/post/6844904093463347208)
- [滴滴前端技术团队](https://juejin.cn/team/6943816493473726472/posts) - 比较硬核的 Webpack 原理分析系列文章，得静下心来慢慢看
  - [你不知道的webpack静态文件生成过程](https://juejin.cn/post/6959449526197288996)
  - [webpack系列之七-文件生成](https://juejin.cn/post/6844903925179482119)
  - [webpack系列之七-附dependencyTemplates依赖模板](https://juejin.cn/post/6844903925171093518)
  - [webpack系列之六chunk图生成](https://juejin.cn/post/6844903864592777229)
  - [webpack系列之五module生成1](https://juejin.cn/post/6844903830266576909)
  - [webpack系列之四loader详解1](https://juejin.cn/post/6844903780769595405)
  - [webpack系列之三resolve](https://juejin.cn/post/6844903779712630797)
  - [webpack系列之二Tapable](https://juejin.cn/post/6844903750729990152)
  - [webpack系列之一总览](https://juejin.cn/post/6844903726981840904)

<hr />

## :mortar_board: 性能优化

- [Web Performance Optimization with Webpack](https://developers.google.com/web/fundamentals/performance/webpack/)
- [Webpack 4: mode and optimization](https://medium.com/webpack/webpack-4-mode-and-optimization-5423a6bc597a)
- [The 100\% correct way to split your chunks with Webpack](https://medium.com/hackernoon/the-100-correct-way-to-split-your-chunks-with-webpack-f8a9df5b7758)
- [iamakulov/awesome-webpack-perf](https://github.com/iamakulov/awesome-webpack-perf)
- [Webpack 构建性能优化探索](https://github.com/pigcan/blog/issues/1)
- [开发工具心得：如何 10 倍提高你的 Webpack 构建效率](https://segmentfault.com/a/1190000005770042)
- [webpack Performance: The Comprehensive Guide](https://github.com/lcxfs1991/blog/issues/15)
- [彻底解决Webpack打包慢的问题](https://segmentfault.com/a/1190000006087638)
- [webpack 构建性能优化策略小结](https://segmentfault.com/a/1190000007891318)
- [彻底解决 webpack 打包文件体积过大](https://www.jianshu.com/p/a64735eb0e2b): 文章介绍 5 种常见的包体积优化方法，行文特别清晰
- [玩转 webpack，使你的打包速度提升 90\%](https://juejin.cn/post/6844904071736852487)
- [ESM vs Webpack 面向高性能构建的探索](https://juejin.cn/post/6947890290896142350)