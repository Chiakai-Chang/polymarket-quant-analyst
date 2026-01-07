# Polymarket Quant Analyst (Project Cassandra)

**Polymarket Quant Analyst** is an advanced Open Source Intelligence (OSINT) research framework designed to assist analysts in estimating the probabilities of complex geopolitical and economic events on prediction markets. By leveraging Large Language Models (LLMs) and rigorous quantitative methodologies, it provides a structured approach to decision-making under uncertainty.

This repository (`polymarket-quant-analyst`) integrates principles from **probabilistic forecasting**, **market microstructure analysis**, and **forensic auditing** to mitigate cognitive biases and identify systemic risks in information markets.

## 🚀 Research Objectives

*   **Cognitive Bias Mitigation:** Utilizing recursive Delphi methods to reduce "hallucination echo chambers" in LLM analysis.
*   **Microstructure Analysis:** Investigating how order book dynamics and liquidity fractures influence probability estimates.
*   **Forensic Rule Auditing:** analyzing resolution criteria and historical precedents (Case Law) to identify edge cases in smart contracts.
*   **Capital Efficiency:** Modeling opportunity costs and friction to determine the mathematical viability of a position.

## 🧠 System Architecture

The core logic is encapsulated in `src/system_prompt.md`. This protocol guides the AI agent through a six-stage analytical pipeline:

1.  **Phase 0: Triage & Configuration** - Event classification and risk profile selection.
2.  **Phase 1: Forensic Audit** - Examination of resolution rules, dead-end risks, and historical precedents.
3.  **Phase 2: Adversarial Simulation** - Multi-agent debate using base rate anchoring and external validation.
4.  **Phase 3: Quant Valuation** - Risk-adjusted probability estimation and capital efficiency modeling.
5.  **Phase 4: Microstructure Analysis** - Evaluation of liquidity depth, spread, and order flow imbalances.
6.  **Phase 5: The Watchtower** - Monitoring protocols for invalidation triggers and resolution windows.

## 🛠️ Usage

### Installation & Execution

This framework relies on **live web crawling** for real-time data verification. We recommend using the official **Gemini CLI**.

**Prerequisites:**
1.  Install **Gemini CLI**: Refer to the [Official Gemini CLI Installation Guide](https://github.com/google/gemini-cli).
2.  Ensure your API Key is set and Search tools are enabled.

**Execution:**
1.  Clone this repository:
    ```bash
    git clone https://github.com/your-username/polymarket-quant-analyst.git
    cd polymarket-quant-analyst
    ```
2.  Run the system prompt:
    ```bash
    gemini chat -s src/system_prompt.md
    ```
3.  Input a target Polymarket URL to begin analysis.

## 📂 Repository Structure

*   `src/system_prompt.md`: The core analytical protocol (v4.0).
*   `docs/examples/`: Case studies and usage examples (e.g., OpenAI Hardware Analysis).
*   `CHANGELOG.md`: Version history and protocol evolution.
*   `LICENSE`: MIT License.

## ⚠️ Disclaimer

**This project is for educational and research purposes only.**
The content produced by this software is AI-generated and experimental. It does not constitute financial, investment, or legal advice. The "strategies" and "valuations" described are theoretical constructs for modeling risk and do not guarantee any real-world outcomes. Users should conduct their own independent research (DYOR).

## 📜 License



MIT



---

*Maintainer: Chia-Kai Chang (lotifv@gmail.com)*


