<p align="center">
  <img src="assets/banner.jpg" alt="PhD Application Research Agent — research, funding and outreach" width="100%" />
</p>

<h1 align="center">PhD Application Research Agent</h1>

<p align="center"><strong>告别傻逼的申请中介，自己和 AI 一起申请 PhD 吧。</strong></p>

<p align="center">
  <strong>简体中文</strong> · <a href="docs/README.zh-TW.md">繁體中文</a> · <a href="README.en.md">English</a> · <a href="docs/README.ja.md">日本語</a> · <a href="docs/README.ko.md">한국어</a> · <a href="docs/README.es.md">Español</a> · <a href="docs/README.fr.md">Français</a> · <a href="docs/README.pt.md">Português</a> · <a href="docs/README.de.md">Deutsch</a>
</p>

<p align="center">
  <a href="PROMPT.md">完整提示词</a> ·
  <a href="#快速开始">快速开始</a> ·
  <a href="#模型与平台设置">模型设置</a> ·
  <a href="README.en.md">English</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/type-AI%20prompt-12665f?style=flat-square" alt="AI prompt" />
  <img src="https://img.shields.io/badge/language-中文-456f88?style=flat-square" alt="Chinese prompt" />
  <img src="https://img.shields.io/badge/license-MIT-c69b45?style=flat-square" alt="MIT license" />
</p>

这是一份用于博士申请的开源提示词。它帮助你和 AI 一起调研导师、核查项目与资金、准备套磁邮件，并记录申请进度。

**每天花约 15 分钟，查看整理好的信息、审阅邮件，决定下一步。** 首次设置、阅读论文、撰写研究计划和正式申请可能需要更多时间。

要运行完整的每日自动流程，**你使用的 AI 平台需要同时支持定时自动化和邮件调用**：能在后台按计划工作，连接邮箱并读取、起草和发送邮件。发送前仍需你确认。联网、文件读取和申请记录的持续保存也要实际可用。

## 致所有 PhD 申请者

> 在开始 PhD 的申请之前，请先在心里问自己，读 PhD 是不是真的自己的意愿。我们做一件事，要去多问问自己是不是自己真的要做某事。
>
> 通过自己而不是中介完成申请，当你拿到 offer 的那一刻一定会无比的快乐。人生是一个随着时间向前狂喜逐渐减少的过程，所以试着让自己的喜悦更加喜悦吧。
>
> 任何中介都是在帮助你做你本可以的事情，你本身就很厉害！一定可以的。
>
> —— Yi Fan

## 我们的想法

我们更看重一套完整的工作流程：把调研、核验、联系和正式申请衔接起来。模型一直在进步，我们信任它的写作能力，不用固定模板和字数来限制它；具体内容由你的研究、偏好和判断决定。

- **何时转向申请：** 首次使用时，会建议你以 8–10 位导师的有效 A/B 回复作为参考，考虑停止新增套磁、开始正式申请。目标可以调整，截止临近时不必等到达标。
- **直接申请也算候选：** 调研无需导师事先同意即可申请的项目，问过你的意愿后分为 A-DIRECT 或 B-DIRECT；与导师回复分开统计。
- **每天看截止：** 查邮件时同步列出各目标的申请、奖学金等截止与剩余时间，也告诉你从今天开始转向申请还剩多久。

## 推荐用云端运行

**强烈建议使用 ChatGPT Work 运行这个工作流**，桌面端、网页版和手机端都可以。桌面端也可以启动云端 Work。如果希望每天早上 10 点即使电脑关机也能运行，请确认定时任务和所需资料、工具都能在云端使用。

如果步骤依赖本机文件或桌面应用，电脑关机或休眠时可能无法访问或执行。本地 Codex 也依赖电脑；Codex Cloud 是另一种云端方式。无论使用哪种方式，先验证定时、联网、邮箱和申请记录的访问，邮件发出前仍由你确认。

特别检查文件访问：ChatGPT 项目中的定时任务不能直接访问上传到项目中的文件，须将资料放在该任务实际可访问的位置并测试。设置时区、做一次实际运行，并检查下次运行时间与报告。功能因账户、套餐和工作区而异。

例如可尝试使用已授权的云端文件或连接服务保存台账，先测试定时任务能否读取和更新同一份记录。

官方说明：[ChatGPT Work 与 Codex](https://help.openai.com/en/articles/20001275/) · [ChatGPT 定时任务](https://help.openai.com/en/articles/10291617-scheduled-tasks-in-chatgpt) · [Codex Cloud](https://help.openai.com/en/articles/20001545-using-codex-cloud)

## 能做什么

| 工作 | 内容 |
| --- | --- |
| 🔎 导师调研 | 根据你的研究问题寻找导师，核对研究成果与具体匹配点。 |
| 🎓 项目与资格 | 检查招生路径、申请周期、资格、材料与截止日期。 |
| 💰 资金调查 | 查找奖学金、学费与生活费支持，分清已确认和待确认的信息。 |
| ✉️ 套磁邮件 | 针对导师和你的真实经历准备完整邮件，供你审阅。 |
| 🗂️ 进度管理 | 整理候选、联系记录、回复、待办事项和申请材料。 |

提示词包含从首次了解申请人到研究、联系、申请准备和进度维护的 **30 个阶段**，适用于不同学科及申请路径。

## 快速开始

1. 打开你常用的 AI 平台，新建对话或项目，并选择可用的模型。
2. 打开 [完整提示词](PROMPT.md)，复制全部内容，粘贴给 AI。
3. 按提示提供研究方向、申请地区、计划入学年份、资金要求和 CV。资料可以分批补充。
4. 授权并确认定时任务与邮箱功能。设置成功后，AI 会按计划主动交付日报；你查看报告、审阅待发邮件并决定下一步。

定时任务按计划运行并交付日报；ChatGPT 的推送或邮件提醒需要在通知设置中开启。即使当天没有新回复，日报也应汇报进度和截止时间。没有自动化功能时，可手动启动。

手动运行时，可以这样开始：

> 继续今天的博士申请工作。先告诉我重要回复、临近截止和需要我决定的事项，再整理今天的导师调研和待审邮件。

## 模型与平台设置

你可以在 ChatGPT、Claude、Gemini、Kimi、DeepSeek 等 AI 平台，或其他支持长提示词的工具中使用。**模型需要在你使用的平台里选择**；提示词无法替你切换模型。

| 设置 | 建议 |
| --- | --- |
| 模型 | 选择适合长文本阅读和研究整理的可用模型。 |
| 推理强度 | 平台提供时，日常任务可选效率合适的档位；复杂文献或冲突信息可提高强度。 |
| 联网与文件 | 有这些功能时开启网页搜索和文件读取，用官方来源核查信息。 |
| 邮箱与定时任务 | 完整自动流程需要这两项；先连接并验证读信、草稿、发信和定时运行能力。 |

各平台的功能、额度和费用由各自服务决定。缺少自动化或发信能力时，仍可使用提示词，但对应步骤需要手动完成。无法联网时，可以提供网页和文件，由 AI 协助整理。

开始时可告诉 AI：你使用的平台、已选模型、推理档位，以及是否可以联网、读取文件或连接邮箱。没有的功能直接写“不可用”。

## 使用时请留意

- 导师、项目、资金和截止日期以当轮官方信息为准；让 AI 给出来源，并核查关键事实。
- 邮件发出前由你审阅和批准。研究问题、申请材料以及最终选择由你决定。
- 这是一份提示词，不会自行连接邮箱、创建定时任务或代你提交申请。

## 参与改进

欢迎提交 [Issue](https://github.com/fanyi3017-stack/phd-application-research-agent/issues) 或 Pull Request，分享遇到的问题和改进建议。贡献方式见 [CONTRIBUTING.md](CONTRIBUTING.md)。

其他语言版本由 AI 辅助翻译，已核对关键规则；如有歧义，以简体中文原文为准，欢迎提出修正。


## 项目范围与社区

这个项目主要负责导师调研和套磁。套磁顺利的话，沟通中的导师可能愿意指导你的研究计划（RP）和后续申请，包括奖学金；具体支持以导师的实际回复为准。遇到拿不定主意的事情，也欢迎加入微信群，和其他申请者讨论。

联系及申请进群：[yifan@curatingmyatery.com](mailto:yifan@curatingmyatery.com)

**扫码加入微信群「OFFRR HODERS」：**

<img src="assets/wechat-group.jpg" alt="OFFRR HODERS WeChat group QR code" width="320" />

若二维码失效，请通过上方邮箱联系。

## 致谢

- 感谢 OpenAI 提供的工具与技术。
- 感谢参与代码开发、文档完善、插件分享和问题排查的所有项目贡献者。
- 感谢持续提供反馈、分享成果并支持项目发展的社区用户。
- 护谜（上海）智能科技有限公司：贡献 Codex 开发算力。

Copyright © 2026 护谜（上海）智能科技有限公司

## 许可

[MIT License](LICENSE) · Yi Fan
