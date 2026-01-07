# Polymarket Quant Analyst (Project Cassandra)

**Polymarket Quant Analyst** 是一個自主的高頻地緣政治預測框架，旨在以量化對沖基金的嚴謹度來分析 Polymarket 事件。它超越了單純的機率估算，整合了市場微結構分析、流動性風險評估以及資本效率計算。

[English README](README.md) | [System Prompt (核心協議)](src/system_prompt.md)

## 🚀 核心哲學 (Core Philosophy)

*   **生存優先 (Survival First)：** 本金保護優於追求超額報酬 (Alpha)。
*   **規則至上 (Rules Over Vibes)：** 對合約結算規則與 UMA 判例進行嚴格的取證審計。
*   **流動性為王 (Liquidity is King)：** 除非明確處於做市商模式，否則避開「殭屍市場」與「流動性陷阱」。
*   **對抗模擬 (Adversarial Simulation)：** 使用遞歸德爾菲法 (Delphi method)，透過多重代理人（法理學家、現實主義者、歷史學家）進行辯論。

## 🧠 系統架構 ("God Mode" Spec)

核心邏輯封裝於 `src/system_prompt.md` 中。此檔案作為 LLM Agent 的「作業系統」，引導其完成六個不同的分析階段：

1.  **Phase 0: Triage & Risk Profile (分流與風險定性)** - 確定事件類型並選擇適當的風險屬性（保守型 vs. 激進型）。
2.  **Phase 1: Forensic Audit (取證審計)** - 掃描「拉地毯 (Rug Pull)」情境、合約死線陷阱以及 UMA 歷史判例。
3.  **Phase 2: Adversarial Simulation (對抗模擬)** - 透過基準率定錨與外部驗證，進行多輪辯論。
4.  **Phase 3: Quant Valuation (量化估值)** - 計算調整了機會成本（時間價值）與摩擦成本後的期望值 (EV)。
5.  **Phase 4: Microstructure Execution (微結構執行)** - 分析掛單簿 (Order Book) 以尋找流動性斷層、虛假掛單 (Spoofing) 與套利機會。
6.  **Phase 5: The Watchtower (瞭望塔)** - 監控失效點 (Invalidation Points) 並管理關鍵的 UMA 爭議窗口。

## 🛠️ 使用方法 (Usage)

### 安裝與執行 (Installation & Execution)

由於本框架包含大量的**即時網路搜索 (Web Crawling)** 與**判例挖掘**，我們強烈建議使用官方的 **Gemini CLI** 來執行此 System Prompt，因為它原生整合了 Google Search 工具。

**前置作業：**
1.  安裝 **Gemini CLI**：請參考 [Google Gemini CLI 官方安裝指南](https://github.com/google/gemini-cli) (或相關官方資源)。
    *   **Windows 用戶**：通常透過 PowerShell 或 WSL 安裝。
    *   **Linux/Mac 用戶**：透過終端機安裝。
2.  確保您已設定好 API Key 並開啟了網路搜索權限。

**執行步驟：**
1.  複製本專案：
    ```bash
    git clone https://github.com/your-username/polymarket-quant-analyst.git
    cd polymarket-quant-analyst
    ```
2.  啟動 Gemini CLI：
    ```powershell
    gemini chat -s src/system_prompt.md
    ```
3.  開始輸入 Polymarket 連結進行分析。

### 觸發指令

**基礎分析：**
> "Analyze [Polymarket URL]"

**進階分析 (提供 HTML 以掃描流動性)：**
> "Analyze [Polymarket URL] with this Order Book HTML: [Paste HTML Code]"

**Agent 將輸出：**
*   **Forensic Report (取證報告)：** 規則中隱藏的風險。
*   **Model Probability (模型機率)：** 經過信心阻尼修正後的數值。
*   **Valuation (估值)：** 此賭注在數學上是否為正 EV。
*   **Tactical Plan (戰術計畫)：** 具體的限價單 (Limit Order) 價格與止損點。

## 📂 專案結構 (Repository Structure)

*   `src/system_prompt.md`: 主協議文件 (v4.0 Professional Edition)。
*   `docs/examples/`: 案例分析 (如 OpenAI 硬體預測)。
*   `README.md`: 英文說明文件。
*   `README_zh-TW.md`: 本文件。

## ⚠️ 免責聲明 (Disclaimer)

本專案僅供教育與研究用途。預測市場涉及重大財務風險。系統提示詞中定義的「門檻率 (Hurdle Rates)」與「安全補丁 (Safety Patches)」均為理論架構，不保證獲利。請務必自行研究 (DYOR)。

## 📜 授權 (License)

MIT

---
*維護者：Chia-Kai Chang (lotifv@gmail.com)*
