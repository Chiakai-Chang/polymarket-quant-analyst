# Polymarket Quant Analyst

**Polymarket Quant Analyst** 是一個先進的開源情報 (OSINT) 研究框架，旨在協助分析人員利用資訊市場作為數據源，估算複雜社會經濟與技術事件的發生機率。透過大型語言模型 (LLMs) 與嚴謹的量化方法論，本框架為不確定性下的決策提供結構化路徑。

本專案 (`polymarket-quant-analyst`) 整合了**機率預測**、**市場微結構分析**以及**取證式數據審計**的原理，以減少認知偏誤並識別去中心化共識機制中的系統性異常。

## 🚀 研究目標 (Research Objectives)

*   **認知偏誤緩解：** 使用遞歸德爾菲法 (Delphi method) 減少 LLM 事件分析中的「幻覺回音室」效應。
*   **微結構分析：** 研究數據掛單深度與流動性如何影響機率估算的準確性。
*   **取證式審計：** 分析結算準則與歷史數據模式，識別基於智能合約之市場中的邊緣案例風險。
*   **數學嚴謹性：** 建模機率分佈與數據摩擦成本，以判斷統計預測的有效性。

## 🧠 系統架構 (System Architecture)

核心邏輯封裝於 `GEMINI.md` 中。此協議引導 AI 代理人完成六個分析階段：

1.  **Phase 0: Triage & Configuration (分流與配置)** - 事件分類與分析屬性選擇。
2.  **Phase 1: Forensic Audit (取證審計)** - 數據源檢查、結構性風險與歷史判例分析。
3.  **Phase 2: Adversarial Simulation (對抗模擬)** - 透過基準率定錨與外部驗證，進行多重代理人辯論。
4.  **Phase 3: Quantitative Assessment (量化評估)** - 風險調整後的機率估算與模型建立。
5.  **Phase 4: Microstructure Evaluation (微結構評估)** - 評估數據深度、價差以及資訊流不平衡。
6.  **Phase 5: The Watchtower (瞭望塔)** - 建立數據失效監控協議與結算窗口預警。

## 🛠️ 使用方法 (Usage)

### 安裝與執行 (Installation & Execution)

由於本框架包含大量的**即時網路搜索 (Web Crawling)**，我們強烈建議使用官方的 **Gemini CLI** 來執行，因為它原生整合了強大的搜索工具。

**前置作業：**
1.  **安裝 Gemini CLI**：
    *   **Windows 用戶推薦：** 先下載並安裝 [nvm-windows](https://github.com/coreybutler/nvm-windows)。安裝後執行 `nvm install latest` 取得最新 Node.js 環境，接著執行 `npm install -g gemini-chat-cli` 即可。
    *   **官方指南：** [Gemini CLI Official Installation Guide](https://github.com/google-gemini/gemini-cli)。
2.  **身分驗證：** 您可以直接透過 `gemini auth login` 使用 Google 帳號登入（推薦 [Google AI Pro](https://one.google.com/intl/zh-TW_tw/about/google-ai-plans/) 用戶使用以獲取更高額度），或設定 API Key。
3.  確保已開啟網路搜索權限。

**獲取專案：**
*   **透過 Git 複製：**
    ```bash
    git clone https://github.com/Chiakai-Chang/polymarket-quant-analyst.git
    cd polymarket-quant-analyst
    ```
*   **直接下載 ZIP：**
    1.  點擊下載 [最新版本 ZIP 檔](https://github.com/Chiakai-Chang/polymarket-quant-analyst/archive/refs/heads/main.zip)。
    2.  將檔案解壓縮至本地資料夾。

**執行步驟：**
1.  在專案目錄下開啟終端機。
2.  啟動**互動式分析會話**：
    ```powershell
    gemini
    ```
3.  系統會自動載入目錄下的 `GEMINI.md` 協議。請直接輸入目標市場連結開始分析。

## 📂 專案結構 (Repository Structure)

*   `GEMINI.md`: 核心分析協議 (v1.0.0)。
*   `docs/examples/`: 案例研究與使用範例 (如：硬體發布機率預測)。
*   `CHANGELOG.md`: 版本歷史與協議演進記錄。
*   `LICENSE`: MIT License。

## ⚠️ 免責聲明 (Disclaimer)

**本專案僅供學術研究與教育用途。**
本專案產出的所有內容均為 AI 生成之實驗性文本，不構成任何財務、投資或法律建議。本工具旨在進行機率建模，而非用於輔助實際交易或博弈行為。使用者應自行進行獨立研究 (DYOR)。

## 📜 授權 (License)

MIT

---
*維護者：Chia-Kai Chang (lotifv@gmail.com)*
