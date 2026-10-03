# AI Software Factory 2.0

從 Agentic Coding 到 Verifiable Software Engineering。

當 AI 可以大量產生程式、測試、文件，軟體工程的瓶頸不再是「寫不出來」，而是「怎麼知道它是對的」。這個 repo 主張：下一階段的 Software Factory 不該只是增加更多 Agent，而是把流程轉成：

```
Specification → Generation → Verification → Evidence → Release
```

AI 負責生成，Formal Specification 定義正確性，Model Checker 負責系統性探索與找反例，測試負責回真實程式重現，人類負責語意與規格裁定。

## 線上閱讀

https://shanchiehchiu.github.io/ai-software-factory-2/

## 內容

| 頁面 | 說明 |
|---|---|
| [index.html](https://shanchiehchiu.github.io/ai-software-factory-2/) | 主文：AI Software Factory 的理念與架構——為什麼需要第二套 correctness engine |
| [implementation.html](https://shanchiehchiu.github.io/ai-software-factory-2/implementation.html) | Formal Verification 實作手冊：Step 0–7 的落地流程（選目標 → 寫規格 → 建模 → 探索 → 回放 → 修復 → 防假綠） |
| [erp-case-study.html](https://shanchiehchiu.github.io/ai-software-factory-2/erp-case-study.html) | ERP 實戰案例：在一個 Laravel ERP 的銷售訂單狀態機上完整跑完一輪的紀實，含兩個真 bug 的發現與修復 |

## 授權

內容為技術心得分享，歡迎引用（請附出處連結）。
