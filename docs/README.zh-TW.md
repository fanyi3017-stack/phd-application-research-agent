<p align="center"><img src="../assets/banner.jpg" alt="PhD Application Research Agent" width="100%" /></p>

<h1 align="center">🎓 PhD Application Research Agent</h1>

<p align="center"><strong>告別傻逼的申請仲介，自己和 AI 一起申請 PhD 吧。</strong></p>

<p align="center"><a href="../README.md">简体中文</a> · <strong>繁體中文</strong> · <a href="../README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.es.md">Español</a> · <a href="README.fr.md">Français</a> · <a href="README.pt.md">Português</a> · <a href="README.de.md">Deutsch</a></p>

<p align="center"><a href="../prompts/PROMPT.zh-TW.md"><strong>完整提示詞</strong></a> · <a href="../LICENSE">MIT License</a></p>

這份開源提示詞幫你和 AI 一起調查導師、核查資金、準備套磁郵件並管理博士申請進度。

**每天花約 15 分鐘查看資訊、審閱郵件並決定下一步。首次設定、閱讀論文和正式申請可能需要更多時間。**

> 完整的每日自動流程需要 AI 平台同時支援定時自動化和郵件調用，經授權連接信箱並讀取、起草及發送郵件；發送前須由你確認。網路搜尋、文件讀取和持續保存申請紀錄也必須可用。

## 💌 致所有 PhD 申請者

> 在開始 PhD 申請之前，請先在心裡問自己，讀 PhD 是不是真的自己的意願。我們做一件事，要多問問自己，是不是真的想做這件事。
>
> 透過自己而不是中介完成申請，當你拿到 offer 的那一刻一定會無比快樂。人生是一個隨著時間向前，狂喜逐漸減少的過程，所以試著讓自己的喜悅更加喜悅吧。
>
> 任何中介都是在幫助你做你本來就可以做到的事情。你本身就很厲害！一定可以的。
>
> —— Yi Fan

## 🧭 我們的想法

我們重視完整的工作流程，把調查、查證、聯絡和正式申請連起來。模型持續進步，我們信任它的寫作能力，不強加固定模板或字數；內容由你的研究、偏好和判斷決定。

- **何時轉向申請：** 首次使用時建議以 8–10 位導師的有效 A/B 回覆作為參考，考慮停止新增聯絡、開始正式申請。目標可調整，截止臨近不必等待達標。
- **直接申請也是候選：** 調查不需導師事先同意即可申請的項目，詢問意願後標為 A-DIRECT 或 B-DIRECT，與導師回覆分開統計。
- **每天看截止：** 檢查郵件時同時列出申請、獎學金等截止與剩餘時間，以及今天開始準備申請還有多久。

## ☁️ 建議在雲端執行

**強烈建議使用 ChatGPT Work 執行這個工作流程**，桌面版、網頁版和手機版都可以。桌面版也可以啟動雲端 Work。如果希望每天上午 10 點即使電腦關機也能執行，請確認排程任務和所需資料、工具都能在雲端使用。

依賴本機檔案或桌面應用程式的步驟，在電腦關機或休眠時可能無法存取或執行。本機 Codex 也依賴電腦；Codex Cloud 是另一種雲端方式。無論選擇哪種方式，先驗證排程、連網、郵箱和申請記錄的存取；寄信前仍需你批准。

特別檢查檔案存取：ChatGPT 專案中的排程任務無法直接存取該專案上傳或儲存的檔案。把記錄放在任務實際可存取的位置並測試；設定時區，實際執行一次，確認下次執行和報告。功能依帳戶、方案和工作區而異。

例如可嘗試用已授權的雲端檔案或連接服務保存記錄，先測試排程任務能否讀取和更新同一份記錄。

官方說明：[ChatGPT Work 與 Codex](https://help.openai.com/en/articles/20001275/) · [ChatGPT 排程任務](https://help.openai.com/en/articles/10291617-scheduled-tasks-in-chatgpt) · [Codex Cloud](https://help.openai.com/en/articles/20001545-using-codex-cloud)

## ✨ 功能

- 調查導師與研究匹配證據
- 核查項目、資格、截止日期和資金
- 準備個人化郵件，追蹤回覆與申請進度

## 🚀 快速開始

1. 在 AI 平台選擇可用模型。
2. 複製完整提示詞到新對話或專案。
3. 提供研究方向、地區、入學年份、資金要求和 CV，可分批提供。
4. 授權並確認排程與郵箱功能。設定成功後，AI 會按計畫主動交付日報；你查看報告、審閱待發郵件並決定下一步。

排程任務按計畫運行並交付日報；如需 ChatGPT 推播或電子郵件提醒，請在通知設定中開啟。即使當天沒有新回覆，日報也應報告進度和截止時間。沒有自動化功能時，可手動啟動。

## ⚙ 模型與平台

可使用 ChatGPT、Claude、Gemini、Kimi、DeepSeek 或其他支援長提示詞的工具。模型在平台內選擇；功能、額度和費用因平台而異。缺少自動化或郵件功能時，對應步驟需要手動完成。

譯文經 AI 協助並核對關鍵規則；如有歧義，以簡體中文原文為準。歡迎提出修正。


## 💬 項目範圍與社群

本項目主要負責導師調研與套磁。溝通順利時，導師可能願意指導研究計畫及後續申請，包括獎學金；具體以導師回覆為準。有拿不定主意的問題，歡迎加入微信群討論。聯絡及申請進群：[yifan@curatingmyatery.com](mailto:yifan@curatingmyatery.com)。

**掃碼加入微信群「OFFRR HODERS」：**

<img src="../assets/wechat-group.jpg" alt="OFFRR HODERS WeChat group QR code" width="320" />

若二維碼失效，請透過上方電子郵件聯絡。

## 🙏 致謝

感謝 OpenAI 的工具與技術，以及所有參與程式碼、文件、外掛、問題排查及提供回饋的貢獻者與社群使用者。[护谜（上海）智能科技有限公司](https://github.com/curatingmysteryshanghai)提供 Codex 開發算力。


## 📄 授權

[MIT License](../LICENSE) · Yi Fan

<p align="center">Copyright © 2026 护谜（上海）智能科技有限公司</p>
