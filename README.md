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
4. 在申请季每天回来查看进展，审阅候选和邮件，告诉 AI 下一步怎么做。

日常可以这样开始：

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

## 许可

[MIT License](LICENSE) · Yi Fan
