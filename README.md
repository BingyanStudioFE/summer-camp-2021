# 2021 冰岩作坊前端组夏令营

## 前言

欢迎你来到冰岩作坊 2021 前端组暑期夏令营！

在开始之前，你需要知道的是：

> 在成为前/后端工程师或测试工程师或全栈工程师之前，你首先得是个工程师！

### 仓库结构与规范：

初始项目架构：

- `Summer-Camp-2021`
  - X（熊逸朗）
    - Notes（空）
    - Project（空）
    - Tasks（空）
  - `README.md`
  - `.gitignore`

目标项目架构：

- `Summer-Camp-2021`
  - `你的文件夹`
    - `Notes`
      - `HTML&CSS.md`
      - `JavaScript.md`
      - `Node.md`
      - `Server.md`
      - `Vue.md`
      - `React.md`
    - `Project`（最后一周项目）
    - `Tasks`
      - `partOfProducts`
      - `React-todo-mvc`
      - `Vue-todo-mvc`
      - `js`
      - `HTML&CSS`
      - `node`
        - `task1`
        - `task2`
        - `task2Plus`
      - `hello.md`
  - `README.md`
  - `.gitignore`

### 导师分配

| 学员   | 导师   |
| ------ | ------ |
| 李会鑫 | 兔宝宝 |
| 丁哲淳 | 兔宝宝 |
| 王艺轩 | 小熊   |
| 崔裕铭 | 小熊   |
| 开健   | gcc    |
| 王广凯 | gcc    |

### 注意事项

1. 以下任务请尽量依次完成, 每完成一项后**向导师报告进度**, 并由导师检查完成情况.
2. 学习任务**请写下学习笔记**, 并将笔记保存在`Notes`文件夹中, 实战任务请在`Tasks`
   目录下创建对应文件夹并**将代码上传到其中**. *实战任务开头会带星标*
3. 任务中遇到困难**请尽可能自己解决**, 如思考并尝试后仍后无法解决可向导师寻求帮助
4. 每天都将当日完成情况做一个小总结, 记录在`README.md`中, 在 11 点前 push 到 github
   (关于此条, 若一开始看不懂可在完成**代码托管 / 版本控制**任务后再执行)

---

**接下来让我们开始紧张刺激的冰岩 `5` 层关卡挑战吧 ~~ Link Start ！！**

---

## Re：从O开始的新手村

### 新手大礼包

| 工具                  | 获取地址                                  |
| --------------------- | ----------------------------------------- |
| Chrome                | https://www.google.com/chrome/            |
| Postman               | https://www.getpostman.com/               |
| 学生大礼包            | https://github.com/ivmm/Student-resources |
| Github Education Pack | https://education.github.com/pack         |

### 代码托管 / 版本控制

> Build software better, together

推荐时长：`0.5` 天

#### 任务目标

1. 创建并拥有一个 Github 账号
2. 了解并掌握 `git` 基本操作
3. Fork 并 Clone `summer-camp-2021`夏令营仓库
4. 在`你的文件夹/Tasks` 添加 `hello.md` 文件并写入 `Hello bingyan!` （1级标题）

**注：这步涉及到后面内容的代码控制，请一定完成好哦！以下所有涉及此仓库的代码记得当日 push**

关键词：git、Github

#### 参考资料

[廖雪峰的 Git 教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

[利用 SSH 连接 Github](https://help.github.com/articles/about-ssh/)

### Markdown

推荐时长：`0.5` 天

#### 任务目标

1. 阅读并了解 markdown 语法规范
2. 熟练使用基本的 markdown 操作

关键词：markdown、typora、简书、插件

#### 参考资料

[原味文档](https://daringfireball.net/projects/markdown/syntax)

[中文文档](https://markdown-zh.readthedocs.io/en/latest/)

### 正确获取知识的姿势(不强求)

> 你看百度的工程师都用在用 Google，所以要什么百度自行车！

推荐时长：`0.5` 天

#### 任务目标

1. 成功翻越 GFW(great fire wall)
2. 能够正常访问 Google、Facebook、Twitter、某hub（不要想歪！）等国外网站
3. （选做）成功申请并使用上 Gmail
4. 修改默认搜索引擎为 Google

关键词：Google、Shadowsocks、Virtual Private Network

#### 参考资料

(基本都是要钱的, 免费的梯子搭起来很费事...)

[lantern](https://github.com/getlantern/download)

[DigitalOcean](https://www.digitalocean.com/)

[shadowsocks](https://shadowsocks.com/)

[socket pro](https://www.socketpro.site/zh/home) 👈这个很推荐

### 挑选一个适合自己的编辑器

> 工欲善其事，必先利其器

推荐时长：`0` 天

#### 任务目标

1. 任选其一：（千万不要浪费太多时间在这个地方，只需安装一个即可）
   - 世界级宝具：**Visual Studio Code**
   - 高冷级宝具：Atom
   - IDE 级宝具：WebStorm
   - 王の宝具：Vim | Emacs
2. 了解并安装适当的插件

关键词：coding

#### 参考资料

[Visual Studio Code](https://code.visualstudio.com/)  
[vscode 插件推荐](https://www.php.cn/tool/vscode/475531.html)

[Atom](https://atom.io/)

[WebStorm 学生授权](https://sales.jetbrains.com/hc/zh-cn/articles/207154369-学生授权申请方式)

### * HTML 与 CSS

> 标记的力量

推荐时长：`1` 天

#### 任务目标

1. 分别使用 Google 搜索 html 和 css 教程
2. 认真阅读并掌握 html 和 css 的用法
3. **掌握理解 `flex` 布局**
4. 动手实践，写小demo
5. 产生相应的笔记

关键词：W3C、HTML5、CSS3

#### 参考资料

[html](http://www.w3school.com.cn/html/)

[css](http://www.w3school.com.cn/css/)

[MDN 文档](https://developer.mozilla.org/zh-CN/docs/Web)

## * ①层：JavaScript 的天下

### JavaScript 基础

> JavaScript 才是世界上最好的语言！Σ（ﾟдﾟlll）

推荐时长：`3` 天

#### 任务目标

1. 学习并掌握基本的 JavaScript

   包含同时不限于以下内容：

   - 基本类型
   - 常见的宿主环境及其全局对象
   - JS 原型链机制
   - JS 异步特性
   - ES6 相关内容

2. 写下学习笔记

3. 写下测试demo

关键词：Ajax、Asynchronous、DOM、ES6

#### 参考资料

[如何循序渐进、有效的学习 JS](https://www.zhihu.com/question/19713563)

[JS 简易教程](http://yanhaijing.com/basejs/)

[MDN 文档](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)

（长期）扎实基础推荐书目：

- JavaScript 高级程序设计
- [YDKJS](https://github.com/getify/You-Dont-Know-JS)
- [Eloquent JavaScript](http://eloquentjavascript.net/)

### * Node.js

> 正义的伙伴！

推荐时长：`1` 天

#### 任务目标

1. 了解 Node 的诞生和发展
2. 安装 Node 最新 **LTS** 版，并尝试阅读 Node 文档
3. 写下笔记
4. 使用 `npm` 命令，初始化 `package.json` 并安装 `colors` 包
5. 新建 `guide.js` 文件，使用 `nodejs` 运行，并尝试用代码在其中输出彩虹色的 `Geek is the new sexy!`

#### 参考资料

[Node.js 是干嘛的](https://www.zhihu.com/question/33578075)

[Node.js](https://nodejs.org/)

[简易 Node.js 教程](https://www.liaoxuefeng.com/wiki/001434446689867b27157e896e74d51a89c25cc8b43bdb3000/001434501245426ad4b91f2b880464ba876a8e3043fc8ef000)

[聊聊 Node.js 的历史](http://gitbook.cn/books/58e796fd09012f0a48761eae/index.html)

[color 库](https://www.npmjs.com/package/colors)

### * BOSS 挑战

推荐时长：`1`天

使用 `nodejs` 构建命令行（问答形式）成员管理系统（静态 `Json` 数据类型，具体需求待定）

## ②层：小试牛刀

> 初次接触完整项目

推荐时长：`1`天（flexible）

#### 任务目标

对产品组任务的idea进行分解，分解成多个功能/页面，使用原生 `js` + `node` 完成某些功能点或某些页面

任务时长视产品组任务量、任务需求、任务难度而定

## ③层：框架之争

如下两种框架二选一

### Vue

> 轻量的第三方库

推荐时长：`4` 天

#### 任务目标

1. 阅读完文档并掌握 vue
2. 写下相应的学习笔记
3. 使用 [新手的姿势](https://cn.vuejs.org/v2/guide/index.html#%E5%A3%B0%E6%98%8E%E5%BC%8F%E6%B8%B2%E6%9F%93) 构建应用
4. 纯`vue`实现完成后可尝试第三方库扩展应用
   - `vue-router`
   - `vuex`
   - ....

关键词：Data Driven、Single Page Application(SPA)

**注：只有当你掌握 node 之后才使用 `vue-cli`**

#### 参考资料

[官方文档](https://www.vue3js.cn/docs/zh/)

[TODOMVC](http://todomvc.com/examples/vue/)

### React

> 优雅的函数式编程

推荐时长：`4` 天

#### 任务目标

1. 阅读完文档并掌握 React
3. 写下相应的学习笔记
4. 使用 [新手的姿势](https://reactjs.org/docs/getting-started.html#try-react) 下的 `Online Playgrounds` 的方法构建应用（推荐使用下载文件到本地再编码）
5. 纯`react`实现完成后可尝试第三方库扩展应用
   - `react-router`
   - `redux`
   - ....

关键词：Data Driven、Single Page Application(SPA)

**注：只有当你掌握 node 之后才使用 `create-react-app`**

#### 参考资料

[官方文档](https://reactjs.org/)

[TODOMVC](https://todomvc.com/examples/react/)

### * BOSS 挑战

使用`React`/`Vue` 完成产品组产品功能需求，同**小试牛刀**，区别：使用框架

推荐时长：`3`天

任务时长视产品组任务量、任务需求、任务难度而定

## ④层：后端之旅

> 不想写后端的前端不是一个好设计 (～o￣3￣)～

推荐时长：`3`天

#### 任务目标

1. 学习使用 `nodejs` 下的 `koa` 或 `express`
2. 使用 `nodejs` 能与数据库连接/交互（推荐使用MongoDB）
3. 使用数据库，更新迭代已完成的命令行成员管理系统
4. 为管理系统搭建简单界面（要求：界面美观，尽量适配）

关键词：服务器编程、非关系型数据库、关系型数据库

### * BOSS 挑战

推荐时长：`1`天

1. 本地部署或购买阿里云学生优惠服务器（不强制要求购买服务器）
2. 部署改完成项目至服务器（推荐使用`nginx`）
3. 发出服务器地址给导师
4. 笔记记入`Server.md`

## ⑤层：剑之试炼

> 独立项目

推荐时长：`7`天

#### 任务目标

1. 使用所学知识独自完成产品组某些产品（推荐使用框架）
2. 熟悉一个项目的基本架构
3. 学会与后台沟通（没有后台自己顶替：）
4. 学会测试

### * BOSS 挑战

**Show me your project**

## Final：最终の战

> 这里是无限遐想的世界

到这里你已经掌握了解决基本问题的技能，接下来的战斗需要更多的是你自己不断的努力来面对这场无尽的战争！

但是，正如前面说到的，你首先得成为一名工程师，所以接下来建议是 **进一步补充巩固工程师的基本素养**

1. **计算机网络**
2. **数据结构和算法**
3. **操作系统**

或者 **继续补充前端的相关知识**

1. **正则表达式**
2. **数据结构和算法**
3. **设计模式**
4. **W3C 标准规范**
5. **ECMAScript 标准规范**
6. **前端工程化**
7. **深入研究框架底层**
8. **深入研究 JavaScript 底层相关知识**
9. **构建跨端应用**

## ref

- [developer roadmap](https://github.com/kamranahmedse/developer-roadmap/tree/master/translations/chinese)

## 附录

- [前端组工具库](https://github.com/BingyanStudioFE/tools)
