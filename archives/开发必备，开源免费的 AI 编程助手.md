# 开发必备，开源免费的 AI 编程助手

AI 大模型的火热，让开发圈近来如虎添翼，各种各样基于 AI 技术的开发者工具和新范式不断涌现，尤其是 GitHub 和 OpenAI 共同推出的 Copilot X，更是一骑绝尘。本文将推荐一些开源或免费的 AI 编程工具，不妨试着用起来。

## CodeGeeX

CodeGeeX 被视为 GitHub Copilot 的免费替代品，也有人称其为国产之光。

CodeGeeX 是一个具有 130 亿参数的多编程语言代码生成预训练模型，由清华大学知识工程实验室团队开发，采用华为 MindSpore 框架实现，使用 20 多种语言的语料库上预训练得到。

它支持多种主流编程语言的高精度代码生成及翻译，支持 VS Code 和 JetBrains IDE，并且完全免费！

## Codeium

“个人永远免费！” Codeium 是开发者们的福音。当然，企业用户需付费，但提供的服务也更多。

目前，Codeium 由 Exafunction 团队开发，主要有两个功能：一是能够理解代码和注释的上下文，自动生成代码；二是可以使用自然语言提问，搜索代码库。

Codeium 支持 70 多种编程语言，包括 C++、Go、Java、PHP、Python、Rust 和 Vue 等，并且兼容 VSCode、JetBrains、Emacs 等主流 IDE。

此外，它还提供免费的聊天功能，不过目前使用 OpenAI API 来执行推理。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

## Cursor

Cursor 是一款基于 GPT-3.5-turbo 的 AI 编程工具。它不仅能够生成 10-100 行代码，还可以打开类似 ChatGPT 的界面，与其交互，修复 lint 错误，自动生成测试和注释。

用户每个月有 100 次的免费额度，或者可以使用自己的 OpenAI API key。收费版本的 Cursor Pro 每个月 20 美元起步，使用次数达到 1.5 万次。

## SQL Chat

SQL Chat 是一个基于聊天的 SQL 客户端，可以用自然语言询问数据库问题和查询数据库。SQL Chat 由 Next.js 构建，国内可直接部署到腾讯云 Web 应用托管服务，国外也可一键部署到 Vercel，同样支持私有化部署，目前支持 MySQL、PostgreSQL、SQL Server。

在数据隐私方面，SQL Chat 本身不保留任何数据，数据库连接存储在本地浏览器中。SQL Chat 仅将表结构发送到 OpenAI API，但不会发送任何表数据。

SQL Chat 是开源的，目前需要用户提供自己的 OpenAI API key 才能使用。

## CodeWhisperer

CodeWhisperer 是亚马逊推出的实时 AI 编程助手，所有个人开发者均可免费使用，企业用户则需付费，且对每月推理请求的数量没有限制。

目前，Amazon CodeWhisperer 支持编写 Python、Java、JavaScript、TypeScript、C#、Go、Rust、PHP、Ruby、Kotlin、C、C++、Shell 脚本、SQL 和 Scala 代码，只需要邮箱注册即可。

CodeWhisperer 还具有安全扫描功能，可以发现难以检测的漏洞并提出修复建议，不过目前仅支持 Python、Java 和 JavaScript 的代码安全扫描。

## IntelliCode

IntelliCode 是由微软开发的一种 AI 编码助手，完全免费，并且支持 VS Code 和 VS IDE。它使用了基于云的 AI 模型，通过分析大量的开源项目，为开发人员提供代码上下文和潜在错误的智能提示和自动完成建议。

Visual Studio IntelliCode 最显著的特点之一是团队自动完成功能（Team Completion），它可以识别团队成员代码中常见的代码模式，并根据这些模式生成自动完成建议，从而提高团队的开发效率和代码风格的一致性。

## Tabnine

Tabnine 是最早的 AI 编程辅助工具之一，以前叫 Codota，支持很多主流的 IDE 和编辑器。

Tabnine 有免费版本，可以与 IntelliCode 相媲美；也有付费的 Pro 订阅版，每月 12 美元起，用户可以根据自己的代码训练私有 AI 模型，保持代码特有的风格。值得注意的是，与 Copilot 相比，Tabnine 无需太多的上下文就能生成代码。

通过使用这些 AI 编程工具，开发者可以显著提高编程效率。如果你还想了解更多关于 AI 编程的技术原理和最新的研究成果，GOTC 2023 AI 编程专题论坛绝对是你不容错过的机会。