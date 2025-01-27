在之前的文章中，我们为小站的 ChatGPT 系列文章做了引子。本篇文章将重点聚焦于 ChatGPT 产品本身，探讨其设计、定位、使用及技术等多个层面。

随着上个月国内多家企业的大模型获得许可并向公众开放，距离进入大模型时代似乎越来越近。

如果您对本系列文章感兴趣，欢迎您先阅读我们的第一篇文章。

## 什么是「GPT」？

不少不太关注科技的朋友容易把「ChatGPT」误称为「ChatGTP」或打成「Chatgpt」，其实这些都是错误的表述。想要准确理解「ChatGPT」，首先需要了解它的名称所代表的含义。

GPT 是「Generative Pre-trained Transformer（生成式预训练 Transformer 模型）」的缩写，下面我们逐一解析这些术语：

> **Generative**：生成式，表明该模型可以生成内容。当您给 ChatGPT 一个问题或提示时，它会尝试生成连贯的文本作为回应。

> **Pre-trained**：预训练，表示在处理特定任务（如回答问题或撰写文章）之前，模型已在大量文本上进行过训练。这使得模型掌握语言结构、语境和常识等信息，从而具备广泛的知识和能力。具体来说，基于 GPT-3.5 的 ChatGPT 是通过包含1750亿个参数、8000亿个单词、原始数据达45TB的语料库进行训练的。

> **Transformer**：一种深度学习模型结构，广泛应用于自然语言处理任务。该结构在论文「Attention Is All You Need」中提出，引入了「注意力机制」以捕捉输入数据中的多样化模式，非常适合处理文本等序列数据。

ChatGPT 作为基于 GPT 架构的应用，专为与用户进行交互而进行优化。凭借其庞大的训练数据，ChatGPT 如同一位「百科全书型学者」，在回答问题、生成文本和与用户进行深入对话方面表现优异。

## OpenAI 如何运营 ChatGPT？

OpenAI 最初将 ChatGPT 作为一款公开测试的产品推出。实际上，在推出前，OpenAI 已构建起一整套 API 服务体系，因此，用户接触到的 ChatGPT 实际上包括「ChatGPT」和「OpenAI API」两种产品。

首先，作为 OpenAI 产品之一的 ChatGPT，用户只能通过官方网址 [ChatGPT](https://chat.openai.com/) 进行访问（尽管存在某些第三方客户端的方式，但这些通常不符合 OpenAI 的使用政策）。

在访问 ChatGPT 时，您可能会在链接中看到以 `cf_` 开头的一串字符参数，这些是 OpenAI 为了应对用户量暴增而接入 Cloudflare 的 CDN 和防护服务所产生的无感验证。

ChatGPT 提供会员服务，即每月20美元的 ChatGPT Plus，允许用户享受更多功能。

而 OpenAI API 则是一种允许开发者调用 OpenAI 训练模型的服务，使用 OpenAI API 开发的第三方 ChatGPT 服务目前非常普遍。需要注意的是，OpenAI API 是按量计费，计费方式基于请求的输入和输出的 Token 数。

> ✅ **正确理解 OpenAI API 和 ChatGPT**

- **用途区别**：
  - OpenAI API 供开发者调用各种模型（如 GPT-4）。
  - ChatGPT 是面向普通用户的工具，允许用户直接提问。

- **功能区别**：
  - API 支持更多定制化功能并可调用函数，甚至支持微调。
  - ChatGPT 开箱即用，支持官方及第三方插件（需 Plus 订阅）。

- **界面区别**：
  - OpenAI API 不提供用户界面。
  - ChatGPT 提供网页版及移动客户端。

- **收费方式区别**：
  - OpenAI API 按量计费，仅支持官网付费。
  - ChatGPT 提供免费版和 Plus 订阅选择，Plus 订阅可通过官网及应用商店进行支付。

## 如何使用 ChatGPT？

使用 ChatGPT 的方式可以分为两部分。

OpenAI 提供了无限的 GPT-3.5 模型使用，而订阅 ChatGPT Plus 的用户可以使用 GPT-4，享受更高的生成速度以及插件和数据分析等独占功能。

有关 OpenAI API，官方按照 Token 对请求进行计费，包括输入和输出的总 Token 数，中文内容的一个汉字占用的 Token 数可能超过一个。

您可以使用 OpenAI 提供的 [Token 计算工具](https://platform.openai.com/tokenizer) 来计算文字使用的 Token 数。

对于国内用户，由于 OpenAI 严格的风控政策，申请 OpenAI API 较为困难。然而，微软将 OpenAI 的服务整合到 Azure 云服务平台，用户可以通过 Azure 提供的 ChatGPT API 使用相关服务。

要注意的是，Azure 对生成内容有更为严格的审查，导致某些生成请求可能被拒绝。

## 结论：如何轻松使用 ChatGPT？

在合适的网络环境下，用户可以直接在官网免费使用 GPT-3.5 模型。然而，由于 OpenAI 限制中国地区的手机号、支付方式及 IP，因此国内用户很难使用真实信息注册账号。

我们提供通过 **ACCPAY** 金融服务的方式使用 ChatGPT，包括官网和 API 的服务。

👉 [野卡 | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)