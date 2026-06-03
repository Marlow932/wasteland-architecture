# Project Index: Audited System Components & Verification Registry

This index serves as the official **Quality Control Registry** for the Wasteland Interactive Architecture Showcase. It maps the 8 key system modules, details their core technology stacks, records their architectural stages, and certifies that all active secrets and proprietary codes have been redacted for public showcase visibility.

---

## 1. System Integration Mapping & Verification Log

The following registry logs the technology stacks and sanitization status of the 8 core operational project areas of this architecture showcase:

| ID | System Module | Primary Technology Stack | Showcase Directory | Architecture Stage | Redaction Certified | IP Protection Method |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- |
| **01** | **Wasteland Core Framework** | Python, FastAPI, Pydantic v2 | `01_wasteland-core-framework/` | ⚙️ Active Prototype (R&D) | **YES** | Absolute paths masked, Win32 API calls abstracted, system prompts replaced with templates. |
| **02** | **ALLIE Meta-Orchestrator** | Asterisk PBX, PJSIP, XTTS v2, Whisper | `02_allie-meta-orchestrator/` | ⚙️ Active Prototype (R&D) | **YES** | VoIP SIP/PJSIP registrar keys stripped, voice samples removed, AGI A-leg IPs redacted. |
| **03** | **Sentinel Security Auditor** | FastAPI, Nmap, Nikto, OWASP ZAP | `03_sentinel-security-auditor/` | ⚙️ SaaS Conceptual Framework | **YES** | Active payment webhook signatures disabled, vulnerability reports and scanner logs abstracted. |
| **04** | **Offline Coding Agent** | `llama.cpp`, NVIDIA CUDA, Continue.dev | `04_offline-coding-agent/` | ⚙️ Workstation Dev Cluster | **YES** | Local file paths sanitized, CUDA hardware-specific volume mounts generalized. |
| **05** | **Map Creation Agent** | MSS Capture, Tesseract OCR, PyAutoGUI | `05_map-creation-agent/` | ⚙️ Experimental Automation | **YES** | GUI coordinate databases abstracted, win32 active window checks generalized. |
| **06** | **Business Suite Frontend** | HTML5, CSS3, Terser, cssnano, PWA | `06_business-suite-frontend/` | ⚙️ Active Release (PWA) | **YES** | Hosting deployment keys removed, sitemap configurations anonymized. |
| **07** | **Valuation & Strategy Agent** | Python, Pandas, Google Sheets API | `07_valuation-strategy-agent/` | ⚙️ Strategic Analytics System | **YES** | Google Cloud Service credentials deleted, proprietary MRR multipliers generalized. |
| **08** | **Marketing & Growth Agents** | YouTube & TikTok Data APIs, ChromaDB | `08_marketing-growth-agents/` | ⚙️ Analytical Outreach Engine | **YES** | TikTok/YouTube client secrets removed, outreach recipient datasets anonymized. |
| **09** | **ALLIE Quant-Trader** | Freqtrade, CCXT, FastAPI, SQLite | `09_allie-quant-trader/` | ⚙️ Active Prototype (R&D) | **YES** | API secrets/tokens replaced by placeholders, local server IPs redacted, trading strategies generalized. |

---

## 2. Ecosystem Resource Exclusions

To maintain a clean and lightweight public repository structure, several large binary resources and non-proprietary reference libraries are excluded from this documentation showcase:

* **Large Language Models Registry**:
  * **Status**: Excluded from direct repository tracking.
  * **Details**: Contains quantized binary LLM files (including instruction-tuned GGUF weights totaling ~24GB) used for offline execution.
  * **Showcase Representation**: Documented purely via structural deployment configuration parameters under `04_offline-coding-agent/` (such as llama.cpp CUDA layering and context length parameters).
* **Reference Template Library**:
  * **Status**: Excluded from direct repository tracking.
  * **Details**: Contains open-source developer templates and role-play blueprints.
  * **Showcase Representation**: Represented contextually as part of the orchestration and role registries under `01_wasteland-core-framework/`.
* **Experimental Graphic Assets**:
  * **Status**: Excluded from direct repository tracking.
  * **Details**: Contains experimental graphic and 3D asset generation files.
  * **Showcase Representation**: Represented via abstract terrain generation descriptions under `05_map-creation-agent/`.

---

## 3. Auditing & Verification Signature

This showcase registry has been verified using automated regex verification scripts and manual reviews to confirm that zero operational IP leaks, active keys, or private domain targets are present.

* **Audit Completion Date**: May 25, 2026
* **Lead Technical Reviewer**: Automated Verification Pipeline (Wasteland System Audit)
* **Status Statement**: **CLEAN / APPROVED FOR PUBLIC SHOWCASE**
