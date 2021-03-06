# dgraph中文文档

## 翻译进度

| Page   |   Progress   | Dog  | Start |  Change    |
| :-----------------: | :-------------: | :-----------: | :------: |  :--------:  |
| [首页](https://github.com/Valdanitooooo/dgraph-docs-zh-cn/blob/master/docs/home/index.md)      | :uk: ![Home](http://progressed.io/bar/100) :cn: | [Valdanito](https://github.com/Valdanitooooo)  | 2018-11-29      |       -       |
| [快速开始](https://github.com/Valdanitooooo/dgraph-docs-zh-cn/blob/master/docs/get-started/index.md) |:uk: ![Get Started](http://progressed.io/bar/100) :cn: | [Valdanito](https://github.com/Valdanitooooo)   |  2018-11-29   | -         |
| [查询语言](https://github.com/Valdanitooooo/dgraph-docs-zh-cn/blob/master/docs/query-language/index.md)  |:uk: ![Query Language](http://progressed.io/bar/10) :cn:  | [JustinRong](https://github.com/JustinRong)   | - | - |
| [GraphQL+- 小技巧](https://github.com/Valdanitooooo/dgraph-docs-zh-cn/blob/master/docs/tips/index.md)      |:uk: ![GraphQL+- Tips and Tricks](http://progressed.io/bar/0) :cn:  |    | -   |      -        |
| [Mutations](https://github.com/Valdanitooooo/dgraph-docs-zh-cn/blob/master/docs/mutations/index.md)      |:uk: ![Mutations](http://progressed.io/bar/0) :cn:  | -       | -   |      -        |
| [客户端](https://github.com/Valdanitooooo/dgraph-docs-zh-cn/blob/master/docs/clients/index.md)   |:uk: ![Clients](http://progressed.io/bar/100) :cn:  | [Valdanito](https://github.com/Valdanitooooo)  | 2018-12-01 |      -        |
| [集群部署](https://github.com/Valdanitooooo/dgraph-docs-zh-cn/blob/master/docs/deploy/index.md)                  |:uk: ![Deploy](http://progressed.io/bar/100) :cn:   | [Valdanito](https://github.com/Valdanitooooo)  | 2018-12-09   |      -        |
| [常见问题](https://github.com/Valdanitooooo/dgraph-docs-zh-cn/blob/master/docs/faq/index.md)                  |:uk: ![FAQ](http://progressed.io/bar/0) :cn:  | - | -      |      -        |
| [具体问题指引](https://github.com/Valdanitooooo/dgraph-docs-zh-cn/blob/master/docs/howto/index.md)    |:uk: ![How To Guides](http://progressed.io/bar/0) :cn:  | -       | -      |      -        |
| [设计理念](https://github.com/Valdanitooooo/dgraph-docs-zh-cn/blob/master/docs/design-concepts/index.md)        |:uk: ![Design Concepts](http://progressed.io/bar/0) :cn: | -   | -      | -         |
| [与同类产品比较](https://github.com/Valdanitooooo/dgraph-docs-zh-cn/blob/master/docs/dgraph-compared-to-other-databases/index.md) |:uk: ![Dgraph Compared to Other](http://progressed.io/bar/100) :cn: | [Valdanito](https://github.com/Valdanitooooo)     | 2018-12-01     | -         |

## 翻译风格

- 不予翻译的名词或术语

    dgraph、Zero、Alpha、Ratel、query、mutations、schema

- 语法高亮标记

    graphql语句：```graphql

    docker-compose语句：```yaml

    golang语句：```go

    json数据：```json

- 将一些原有的标记替换掉

    如{{% notice "note" %}}、{{% notice "tip" %}} 、{{% notice "warning" %}} 等，这些dgraph文档原有的标记markdown无法直接解释，替换成如下格式：

    ```html
    **注意** *note内容......*
    **提示** *tip内容......*
    **警告** *warning内容......*
    ```

## 翻译工具推荐

>[谷歌翻译](https://translate.google.com)

>[百度翻译](https://fanyi.baidu.com/translate)

>[Bing词典](http://cn.bing.com/dict/)

>[词都](http://www.dictall.com/)

>[词博](http://www.cibo.cn/)

## 运行项目

- clone项目源码

    ```bash
    git clone git@github.com:Valdanitooooo/dgraph-docs-zh-cn.git
    ```

- 方式一：本机运行（需要node环境）
  
    安装docsify-cli, 关于[docsify](https://docsify.js.org)

    ```bash
    npm i docsify-cli -g
    ```

    在项目根目录下执行：

    ```bash
    docsify serve ./docs
    ```

    访问项目主页http://localhost:3000

- 方式二：docker容器运行（需要docker环境）
  
    在项目根目录下执行：

    ```bash
    docker-compose up -d
    ```

    访问项目主页http://localhost:3000
