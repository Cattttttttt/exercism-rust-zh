# exercism/rust [![explain]][source] [![translate-svg]][translate-list]

<!-- [![size-img]][size] -->

[explain]: http://llever.com/explain.svg
[source]: https://github.com/chinanf-boy/Source-Explain
[translate-svg]: http://llever.com/translate.svg
[translate-list]: https://github.com/chinanf-boy/chinese-translate-list
[size-img]: https://packagephobia.now.sh/badge?p=Name
[size]: https://packagephobia.now.sh/result?p=Name

「 [exercism.io](exercism.io) 的 Rust 练习 」

[中文](./readme.md) | [english](https://github.com/exercism/rust)

---

## 校对 🀄️

<!-- doc-templite START generated -->
<!-- repo = 'exercism/rust' -->
<!-- commit = 'a390d5d84b51507f04d6125979abe5e42a42e7ae' -->
<!-- time = '2018-11-04' -->

| 翻译的原文 | 与日期        | 最新更新 | 更多                       |
| ---------- | ------------- | -------- | -------------------------- |
| [commit]   | ⏰ 2018-11-04 | ![last]  | [中文翻译][translate-list] |

[last]: https://img.shields.io/github/last-commit/exercism/rust.svg
[commit]: https://github.com/exercism/rust/tree/a390d5d84b51507f04d6125979abe5e42a42e7ae

<!-- doc-templite END generated -->

- [ ] readme
- [x] [hello world](./source/exercises/hello-world/README.zh.md)
- [x] [千兆秒-Gigasecond](./source/exercises/gigasecond/README.zh.md)
- [ ] [闰年-Leap](./source/exercises/leap/README.zh.md)
- [x] [雨滴声-Raindrops](./source/exercises/raindrops/README.zh.md)
- [ ] [反转字符串-Reverse String](./source/exercises/reverse-string/README.zh.md)

### 贡献

欢迎 👏 勘误/校对/更新贡献 😊 [具体贡献请看](https://github.com/chinanf-boy/chinese-translate-list#贡献)

## 生活

[help me live , live need money 💰](https://github.com/chinanf-boy/live-need-money)

---

# 运动铁轨

[![Build Status](https://travis-ci.org/exercism/rust.svg?branch=master)](https://travis-ci.org/exercism/rust)
[![Join the chat at https://gitter.im/exercism/rust](https://badges.gitter.im/exercism/rust.svg)](https://gitter.im/exercism/rust?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Rust 的运动练习

### 目录

<!-- START doctoc -->
<!-- END doctoc -->

## 特约

非常感谢您的贡献!:田田:

请阅读有关如何[参与一个轨道](https://github.com/exercism/docs/tree/master/contributing-to-language-tracks).一定要阅读练习[行为守则](https://exercism.io/code-of-conduct).

我们欢迎各种拉动请求.没有贡献太小.

我们鼓励为现有练习提供修复和改进的贡献.请注意,该曲目的练习必须符合中描述的练习全行标准[文件](https://github.com/exercism/docs/tree/master/language-tracks/exercises).如果您不确定如何进行更改,请继续打开 GitHub 问题,我们将对其进行讨论.

## 运动测试

在最基本的层面上,练习就是测试.您可以阅读更多关于我们如何考虑测试套件的信息[运动文件](https://github.com/exercism/docs/blob/master/language-tracks/exercises/anatomy/test-suites.md).

测试文件应使用以下格式:

```
extern crate exercise_name;

use exercise_name::*;

#[test]
fn test_descriptive_name() {
    assert_eq!(exercise_function(1), 1);
}

#[test]
#[ignore]
fn test_second_and_past_tests_ignored() {
    assert_ne!(exercise_function(1), 2);
}
```

## 打开一个问题

如果您打算进行重大或重大更改,请打开一个问题,以便我们先讨论.如果这是一个与 Rust 轨道不仅仅相关的讨论,请在中打开一个问题[exercism /讨论](https://github.com/exercism/discussions/issues).

## 提交拉取请求

拉动请求应该集中在单个练习,问题或概念上的内聚变化上.请参考 Exercism's[拉请求指南](https://github.com/exercism/docs/blob/master/contributing/pull-request-guidelines.md).

请遵循 Rust 的编码标准.[rustfmt](https://github.com/nrc/rustfmt)可以帮助这个,可以安装`cargo install rustfmt`.

### 验证您的更改

在提交拉取请求之前,您需要以两种方式验证更改:

- 运行 Rust 练习的所有测试
- 运行特定于运动特性的 linter 来验证轨道

Rust 练习的所有测试都可以从 repo 的顶层运行`_test/check-exercises.sh`.如果您使用的是 Windows 计算机,则需要额外的计算机[特定于 Windows 的说明](_test/WINDOWS_README.md)运行这个.

### 修改练习的自述文件

请注意,每个练习的自述文件都是使用几个模板形成的,并非所有模板都必须存在于此回购中.其中最重要的是:

- 该`description.md`文件在运动目录中[问题规范库](https://github.com/exercism/problem-specifications/tree/master/exercises)

- 该`.meta/hints.md`文件存储在此存储库的 exercise 目录中

- 该[特定于 Rust 的说明](https://github.com/exercism/rust/blob/master/config/exercise-readme-insert.md)

如果要修改属于模板的 README 部分而不是来自此存储库,请考虑[打开公关](https://github.com/exercism/problem-specifications/pulls)在...上`problem-specifications`存储库首先.

## 贡献一项新的练习

请参阅有关的文档[添加新练习](https://github.com/exercism/docs/blob/master/you-can-help/make-up-new-exercises.md).

注意:

- 生成,更新或配置练习的最简单方法是使用[行使](https://github.com/exercism/rust/tree/master/util/exercise)此存储库中提供的实用程序要编译该实用程序,您可以使用[斌/ build_exercise_crate.sh](https://github.com/exercism/rust/tree/master/bin/build_exercise_crate.sh)脚本,或者,如果脚本不适合您,请使用`cargo build --release`命令在`util/exercise/`目录然后复制`exercise`从二进制文件`util/exercise/target/release/`目录进入`bin/`目录.使用`bin/exercise --help`了解现有命令及其可能的用法.请注意,此实用程序取决于`reqwest`箱子,因此您可能需要安装它[必需的图书馆](https://github.com/seanmonstar/reqwest#requirements)(即`openssl`)在你的系统中.

- 每项运动都必须独立运作.不要引用 exercise 目录之外的文件.当用户提取练习时,不会包括它们.

- 练习必须符合中描述的全运动标准[文件](https://github.com/exercism/docs/tree/master/language-tracks/exercises).

- 每项练习都应该:

  ```
  exercises/exercise-name/
                          tests/exercise-name.rs  <- a test suite
                          src/lib.rs              <- an empty file or with exercise stubs
                          example.rs              <- example solution that satisfies tests
                          Cargo.toml              <- with version equal to exercise definition
                          Cargo.lock              <- Auto generated
                          README.md               <- Instructions for the exercise (see notes below)
  ```

- 存根文件和测试套件应仅使用 Rust 核心库.`Cargo.toml`不应该列出任何外部依赖项,因为我们不想让学生假设所需的板条箱.如果`example.rs`使用外部包装箱,包括`Cargo-example.toml`以便`_tests/check-exercises.sh`可以在测试时用这些编译.

- 除非在特殊情况下,存根文件应在下编译`cargo test --no-run`.这允许我们检查存根文件中的签名是否与测试所期望的签名匹配.使用`unimplemented!()`作为每个功能的身体来实现这一点.如果有一个合理的理由说明为什么这是不可能的,那么包括一个`.meta/ALLOWED_TO_NOT_COMPILE`包含原因.

- 如果从具有 a 的问题规范移植现有练习`canonical-data.json`文件,使用中的版本`canonical-data.json`作为你的运动`Cargo.toml`版.否则,使用"0.0.0".

- 练习可能包含`.meta/hints.md`.这是可选的,如果存在,将出现在正常的运动指示之后.Rust 在很多方面与其他语言不同.这是一个解释 Rust 所需差异的地方.如果这是一个很大的变化,你可能想把它作为评论在顶部`src/lib.rs`,因此用户在开始之前会认识到阅读本节.

- 如果通过在发布模式下运行来明显加速测试套件,并且有理由确信示例实现不包含任何溢出错误,请考虑添加文件`.meta/test-in-release-mode`.这应该包含解释情况的简短评论.

- 如果你的练习实现了基于宏的测试(参见[#392](https://github.com/exercism/rust/issues/392#issuecomment-343865993)和[`perfect-numbers.rs`](https://github.com/exercism/rust/blob/master/exercises/perfect-numbers/tests/perfect-numbers.rs)),你可能会碰到一个 CI 检查计数器`#[ignore]`行并将结果与 ​​ 数字进行比较`#[test]`线.要解决此问题,请添加文件`.meta/ignore-count-ignores`禁用该检查以进行锻炼.

- `README.md`也许[再生](https://github.com/exercism/docs/blob/master/maintaining-a-track/regenerating-exercise-readmes.md)来自运动数据.发电机将使用`description.md`从运动目录中[问题规范库](https://github.com/exercism/problem-specifications/tree/master/exercises),然后任何提示`.meta/hints.md`那么[特定于 Rust 的说明](https://github.com/exercism/rust/blob/master/config/exercise-readme-insert.md).该`## Source`部分来自`metadata.yml`在同一目录中.惯例是源的描述仍然是文本,链接是降价链接的名称和超链接.

- 一定要将练习添加到适当的位置`config.json`文件.文件中的位置确定发送订单练习.为练习生成唯一的 UUID.目前使用的难度级别为 1,4,7 和 10.
