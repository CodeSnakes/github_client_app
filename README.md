# github_client_app

A new Flutter project.
本章新建一个Flutter工程，实现一个简单的Github客户端。这个实例的主要目标有两个：


## OverView

带领读者了解如何使用Flutter来开发一个完整APP，了解Flutter应用开发流程及工程结构等。
对前面章节所学内容的一个应用及总结。
需要注意的是，由于Github本身功能非常多，我们的焦点并不是去实现Github的所有业务功能。因此，我们只需要实现一个APP的骨架，能达到上面这两点即可。下面对我们要实现的功能如下：

- 实现Github账号登录、退出登录功能
- 登录后可以查看自己的项目主页
- 支持换肤
- 支持多语言
- 登录状态可以持久化；
- 要实现上面这些功能会涉及到如下技术点：

- 网络请求；需要请求Github API。
- Json转Dart Model类；
- 全局状态管理；语言、主题、登录态等都需要全局共享。
- 持久化存储；保存登录信息，用户信息等。
- 支持国际化、Intl包的使用

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
