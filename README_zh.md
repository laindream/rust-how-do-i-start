# Rust :crab:. 如何开始？

针对这个经常被问到的问题，这是一个Github仓库，任何人都可以参与并进行改进！

* 👁️ 在你开始之前，请先观看这个仓库（Github观看按钮），这样当我们添加内容时你可以收到更新
* 👾 先玩玩这个页面！花一个小时浏览一下从头到尾的所有链接内容。观看一些视频，浏览几篇博客。然后从主线路开始。
* 👷‍♀️ 当你在学习的过程中，随时可以在[讨论](https://github.com/jondot/rust-how-do-i-start/discussions)中提问关于如何开始学习Rust的问题
* 🎊 随时提出建议和自己的PR：https://github.com/jondot/rust-how-do-i-start#contributing

## 🐱 期待什么？

_精选一些文章，让你了解学习Rust的过程是什么样的。_

* [编写了30k行Rust代码后的我的关键经验](https://jondot.medium.com/my-key-learnings-after-30-000-loc-in-rust-a553e6403c19) - 我可以说现在的体验比以前要好得多。有更多的学习资源，生态系统也更庞大。不过，文章中的核心观点仍然是相关的。

# 🚜 主线路

_这基本上是你应该遵循的学习路径。它是精选的、最小的、高价值的、高效的内容_

* 📚 阅读（代码或文本）
* 🏋️‍♀️ 练习
* 🏗️ 构建

1. 🦀 📚[Rust Book](https://doc.rust-lang.org/book/)。你可以从头到尾阅读，也可以浏览。无论你做什么，确保你有一个实验性的项目想法。你可以选择📚[你喜欢的任何核心工具](https://github.com/uutils/coreutils/tree/main/src/uu)。重新实现一个核心工具的好处是，你可能熟悉其中的一个，它们只是CLI应用程序，你不会咬掉自己嚼不动的东西，而且你在那个仓库里有源代码可以参考。
* 🎬 有点迷茫？你可以观看[使用Rust入门：理解Rust编译错误](https://www.youtube.com/watch?v=hgZQJys2zpY)，以及[第二部分](https://www.youtube.com/watch?v=9391GxkYPyY)，这是一个关于错误、借用检查器等内容的_很好的_介绍。
* 🥸 如果你是从动态编程语言过来的，阅读过程可能不那么“流畅”，需要更多地思考类型和类型系统。如果你遇到困难，想把概念“翻译”成你自己的动态世界，可以随时在[这里](https://github.com/jondot/rust-how-do-i-start/discussions)提问。
* 🫶 你不必把它从头到尾读完。首先，做一个简单的、能正常工作的命令行应用程序。
* 🏋️‍♀️ 如果你喜欢用练习作为学习辅助工具，可以在阅读Rust书的同时，用🏋️‍♀️[rustlings](https://github.com/rust-lang/rustlings)替换“建立一个小项目”。

2. 🧰 选择一个对你有用的业余项目。这个项目要比琐碎的项目稍微复杂一点，包括数据传递和几个模块（这样你就能体验到借用检查器和数据建模），就像🏗️[bat](https://github.com/sharkdp/bat/tree/master/src)的范围。边做边回顾Rust书籍（当然还有StackOverflow）。重复、清洗。
* 🤷‍♀️ 没有业余项目的想法？🏋️‍♀️[PNGMe](https://picklenerd.github.io/pngme_book/introduction.html)是一个很好的要建立的项目，同时它是一本书和练习格式。也可以查看[项目想法列表](https://github.com/jondot/rust-how-do-i-start#-project-ideas)。
* 🎩 根本不想做项目？🏋️‍♀️[太多列表](https://rust-unofficial.github.io/too-many-lists/index.html)这本小书会让你建立各种类型的链表，非常好。
3. 🤝 鼓励寻求反馈，以便更好地编写符合惯例、易读和高性能的Rust代码。你可以在[the Rust Subreddit](https://reddit.com/r/rust)或[the Rust Programming Language Community Discord Server](https://discord.gg/rust-lang-community)中寻求反馈。
4. 📐 📚[Rust API 指南](https://rust-lang.github.io/api-guidelines/)解释了事物为什么是现在的样子。例如，为什么是`into`，以及为什么是`_mut`后缀。当你阅读别人的代码时，了解你周围的Rust-"isms"。
5. 🌱 你现在可以开始学习🏋️‍♀️[Rust 示例](https://github.com/rust-lang/rust-by-example) 和 🏋️‍♀️[Rust 实践](https://github.com/sunface/rust-by-practice)
6. ⏫ 📚[Rust 模式](https://rust-unofficial.github.io/patterns/intro.html) 是一个很好的Rust习语介绍
7. 🚀 接下来，📚[从零到生产的Rust](https://www.zero2prod.com/) 将为你提供一些类似服务和生产环境的用例，这将使你的学习更加圆满
8. 🤔 当你对“为什么”感到好奇时，请阅读📚[Rustaceans的Rust](https://nostarch.com/rust-rustaceans)。浏览并阅读对你感兴趣的部分，通读整本书可能会很难，除非你有集中精力的时间。

从这里开始，因为每个人的口味不同，可以时不时地访问 📚[Rust 书籍](https://lborb.github.io/book/)，以找到你认为可以帮助你迈向下一步的资源。

## 📦 入门库 - 帮我选🤦‍♀️！
_这些是有观点的，但受欢迎的选择。目的是在学习过程中避免[选择困难症](https://en.wikipedia.org/wiki/The_Paradox_of_Choice)。_

* [anyhow](https://docs.rs/anyhow/latest/anyhow/) 用于错误处理
* [clap](https://docs.rs/clap/latest/clap/) 用于构建命令行界面
* [serde](https://serde.rs/) 用于序列化，包括 [serde_json](https://github.com/serde-rs/json) 和 [serde_yaml](https://github.com/dtolnay/serde-yaml)
* [dialoguer](https://docs.rs/dialoguer/latest/dialoguer/) 用于命令行提示和 [console](https://crates.io/crates/console) 用于处理ANSI颜色和处理
* [env_logger](https://docs.rs/env_logger/latest/env_logger/) 用于记录和 [log](https://docs.rs/log/latest/log/) 用于外观
* [lazy_static](https://docs.rs/lazy_static/latest/lazy_static/) 用于声明具有非平凡初始化的静态变量
* [rayon](https://github.com/rayon-rs/rayon) 用于基于数据、向量、数组的工作负载的简单并发
* [reqwest](https://docs.rs/reqwest/latest/reqwest/) 和 [reqwest-middleware](https://crates.io/crates/reqwest-middleware) 用于HTTP调用
* [actix-web](https://docs.rs/actix-web/latest/actix_web/) 作为Web/API服务器
* [nom](https://crates.io/crates/nom)（解析器组合子）或 [pest](https://pest.rs/)（解析表达式文法）用于构建自定义解析器
* [insta](https://crates.io/crates/insta)、[wiremock](https://crates.io/crates/wiremock) 和 [fake](https://crates.io/crates/fake) 用于测试
* [tap](https://crates.io/crates/tap) 用于实用程序

## :ok_hand: 用Rust思考
_精选材料，为您提供Rust演变的背景、原因和历史。其中一些是历史性的。_

* [Rust编程技巧（YouTube）](https://www.youtube.com/watch?v=vqavdUGKeb4) - 2018年的一次演讲，更多关于"用Rust思考"，鼓励使用更多Rust构造。
* [@jonhoo 关于Rust琐事](https://github.com/rusty-ferris-club/jonhoo-rust-trivia) （[Twitter：@jonhoo](https://twitter.com/jonhoo)）
* [@jonhoo 关于Rust关键字](https://github.com/rusty-ferris-club/jonhoo-rust-trivia/blob/main/keywords.md) （[Twitter：@jonhoo](https://twitter.com/jonhoo)）
* [入门Rust：理解Rust编译错误](https://www.youtube.com/watch?v=hgZQJys2zpY)，以及[第2部分](https://www.youtube.com/watch?v=9391GxkYPyY) - 与Ryan Levick一起探索和理解编译器错误和借用检查器的现场课程

## 🥇 金块
_Rust中特定主题的优秀文章、博客、视频，必读或必看_
* [错误处理不仅仅是关于错误](https://www.youtube.com/watch?v=rAF8mLI0naQ) - 来自RustConf 2020的一次演讲，为Rust中的错误处理和错误库提供了出色的概述、细分和终极技巧

## 💡 项目想法
_这些是简单的入门项目想法，不是大型项目，只是为了让您迅速启动。_

* `cat`、`grep`、`uniq`、`wc`、`find` + 更多。 [在这个仓库](https://github.com/kyclark/command-line-rust) 来自 _命令行Rust_ 一书。 -- `练习` CLI，标准库，数据。`难度` 容易。
* [功能强大的计算器](https://crates.io/crates/eva) -- `练习` 命令行界面, 解析, 数据. `难度` 简单.
* [用Rust实现Go中的SMTP协议](https://notes.eatonphil.com/handling-email-from-gmail-smtp-protocol-basics.html) 并从头构建一个简单的TCP服务器 -- `练习` 命令行界面, 解析, 服务. `难度` 简单
* [CloudFormation解析器](https://rtoch.com/posts/advanced-serde/) -- `练习` 命令行界面, serde, 错误, 数据. `难度` 中等.
* [用Rust实现Realworld](https://github.com/gothinkster/realworld) 参见 [realworld-axum-sqlx](https://github.com/launchbadge/realworld-axum-sqlx) -- `练习` Web, 服务, SQL, 数据. `难度` 中等.
* [QR码生成器](https://github.com/madprops/qool) -- `练习` 命令行界面, 模块, 数据. `难度` 中等.
* [Redis协议解析器 (RESP)](https://redis.io/docs/reference/protocol-spec/) -- `练习` 解析, TDD, 创建Rust库, 数据. `难度` 中等.
* [为Clippy添加一个lint](https://github.com/rust-lang/rust-clippy/blob/master/doc/adding_lints.md) Clippy是Rust的linter，您可能一整天都在使用它。那么为什么不添加一些东西呢？ `练习` 真实世界的Rust, 解析, 编译器. `难度` 困难.
* [JSON日志查看器，命令行界面](https://github.com/gistia/json-log-viewer) -- `练习` 命令行界面, TUI, 模块, 数据, 解析. `难度` 困难.

## 🤘 寻找与他人合作的机会
_寻找热衷于Rust的人，共同为了乐趣而构建东西。_
* [Rusty Ferris Club](https://github.com/rusty-ferris-club) 构建基于Rust的小型开源项目，您可以添加自己的[创意或请求](https://github.com/rusty-ferris-club/build-it-for-me-please)

## 🤾‍♂️ 等等！在决定开始之前，我想先试试
_如果您还没有准备好迈出这一步，或者需要一些说服才能投入时间，以下是一些链接_
* 尝试 [rust之旅](https://tourofrust.com/index.html)
* [Rust温和入门](https://stevedonovan.github.io/rust-gentle-intro/readme.html)
* [用Rust迈出第一步](https://docs.microsoft.com/en-us/learn/paths/rust-first-steps/)

## 💻 工作时请在标签页中打开这些很酷的东西
_如果你有多个屏幕，并喜欢全方位的学习体验 - 你可以一直保持这些页面打开_

* [大型速查表](https://www.cheats.rs/) 或 [小型速查表](https://upsuper.github.io/rust-cheatsheet/)
* 有趣的 [语法解释器](https://jrvidal.github.io/explaine.rs/)
* [awesome-rust](https://github.com/rust-unofficial/awesome-rust) 和 [我们到了吗](https://wiki.mozilla.org/Areweyet) 当你需要一个库或灵感时

## 🚀 发布

- [为你的项目和crates提供的 CI/CD 模板](https://github.com/SpectralOps/rust-ci-release-template)
- [给你的crate编写文档](https://blog.guillaume-gomez.fr/articles/2020-03-12+Guide+on+how+to+write+documentation+for+a+Rust+crate)

# 心理桥梁
_当你从Node.js过渡时，这些链接将帮助你建立心理模型_

## 我是一个 Node.js 开发者

1. 添加 [给 Node.js 开发者的 Rust](https://github.com/Mercateo/rust-for-node-developers) 到你的学习计划，这是一个温和的入门，让你找到方向。

## 我是一个 Python 开发者
1. 查看 [从 Python 进入 Rust](https://github.com/rochacbruno/py2rs)

# 贡献

请随时提交 PR 来改进此列表。一些建议：

1. 列表必须简洁
2. 如果有新的学习路径，请随时添加一个新的副标题到这个README并提交PR（例如：“我是游戏开发者，如何开始学习Rust？”）

祝你编程愉快！