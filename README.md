> 一切皆模块，代码更清晰。

## 简介
FangFIS 是房天下前端（包括js, css, images）集成解决方案，主要解决前端工程化 、资源加载（压缩、合并、异步、按需、依赖管理）、模块化开发、自动化等问题，由两部分组成。

1. Fang.js，一个基于CMD模块化思想、适用于 Web 浏览器端的模块加载器。使用 Fang.js，可以更好地组织 JavaScript 代码。它可以轻松集成 jQuery（可选），在使用过程中，无需再额外加载。Fang.js 支持JS资源文件的动态合并加载、异步加载、按需加载和依赖管理。使用 Fang.js，可以更好地组织 JavaScript 代码。

2. FangFIS-CLI，一个基于 Gulp 的自动化构建工具。通过一些简单的命令行操作，支持 CSS 的压缩、JS 的 ES6 转 ES5、合并、压缩、混淆等功能，并且会自动添加模块ID，模块依赖。通过 FangFIS 结合 Fang.js，我们可以方便快速地处理前端静态资源文件，减少了多余的工作，提高开发效率和代码性能。

## 特性

FangFIS 追求简单、自然的代码书写和组织方式，无论是中小型站点，还是大型复杂应用，使用 FangFIS，都可以让我们的工作变得更轻松愉悦。FangFIS 具有以下核心特性：
- **简单友好的模块定义规范：**Fang.js 遵循 CMD 规范，可以像 Node.js 一般书写模块代码。
- **自然直观的代码组织方式：**简洁清晰的配置，依赖的自动加载或合并加载、可以让我们更多地享受编码的乐趣。
- **依赖的自动管理：**只要按照指定的方式声明并引入依赖模块，Fang.js 就会自动按照 JS 代码的执行顺序引入并加载对应的模块代码。
- **脚本的异步加载：**考虑到代码加载量和运行性能，Fang.js 还支持模块的异步加载。
- **友好的调试：**Fang.js 支持开发者根据开发需求自定义自动加载开发环境或者生产环境的代码，方便调试。
- **自动化工作流：**通过自动化构建工具，可以方便快速地完成代码的压缩与合并，一方面减少工作量，另一方面提升页面加载性能。

FangFIS 带来的最大好处是：提升代码的可维护性。上面的每一项特性，在使用文档中都会有详细阐述。如果一个站点的 JS 文件超过 3 个，就适合用 FangFIS 来组织和维护代码。涉及的 JS 文件越多，FangFIS 就越适合。

## 兼容性

```
Desktop

- Internet Explorer: 9+               ✔
- Edge: 12+                           ✔
- Chrome: 40+                         ✔
- Safari: 9+                          ✔
- Firefox: 40+                        ✔
- Opera: 30+                          ✔


Mobile

- Stock browser on Android 4.0+       ✔
- Safari on iOS 7+                    ✔
```

FangFIS 构建的代码也可以运行在 Mobile 端，包括 Hybrid 模式的 App 上。

兼容性覆盖大部分主流浏览器近几年的主流版本，保首起见，均从近期版本写起。理论上所有支持 ECMAScript 5 的浏览器都能够兼容。

## 示例

可以查看 [示例](quickstart.md) 来了解。