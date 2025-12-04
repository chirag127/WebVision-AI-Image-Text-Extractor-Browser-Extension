# WebVision-AI-Image-Text-Extractor-Browser-Extension

![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/WebVision-AI-Image-Text-Extractor-Browser-Extension/ci.yml?style=flat-square)
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/WebVision-AI-Image-Text-Extractor-Browser-Extension?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-4.x-blue?style=flat-square)
![Vite](https://img.shields.io/badge/Vite-4.x-purple?style=flat-square)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.x-cyan?style=flat-square)
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgray?style=flat-square)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/WebVision-AI-Image-Text-Extractor-Browser-Extension?style=flat-square)

**Elevate web accessibility and information extraction with WebVision.** This elite browser extension empowers users to extract text from any image on a webpage using Gemini AI, coupled with real-time Text-to-Speech delivery for unparalleled accessibility and efficiency.

[⭐ Star this Repo](https://github.com/chirag127/WebVision-AI-Image-Text-Extractor-Browser-Extension)

---

## 🚀 Project Overview

WebVision is a cutting-edge browser extension designed to break down visual barriers on the web. By integrating with the advanced Gemini AI model, it provides seamless Optical Character Recognition (OCR) and Text-to-Speech (TTS) capabilities directly within your browser. This transforms static images containing text into accessible, actionable information.

---

## 🌳 Project Structure


.github/
├── issue_template/
│   └── bug_report.md
├── workflows/
│   └── ci.yml
├── CONTRIBUTING.md
├── ISSUE_TEMPLATE.md
├── PULL_REQUEST_TEMPLATE.md
└── SECURITY.md
├── AGENTS.md
├── badges.yml
├── LICENSE
├── .gitignore
├── README.md
├── PROPOSED_README.md
└── tsconfig.json
└── vite.config.ts
└── src/
    ├── content/
    ├── hooks/
    ├── pages/
    ├── components/
    ├── services/
    ├── utils/
    └── main.ts
└── package.json
└── vite.config.ts


---

## 📜 Table of Contents

*   [🚀 Project Overview](#-project-overview)
*   [🌳 Project Structure](#-project-structure)
*   [💡 Key Features](#-key-features)
*   [⚙️ Technology Stack](#-technology-stack)
*   [🤖 AI Agent Directives](#-ai-agent-directives)
*   [🛠️ Development Setup](#-development-setup)
*   [✅ Scripts](#-scripts)
*   [🛡️ Principles & Standards](#-principles--standards)
*   [🤝 Contributing](#-contributing)
*   [⚖️ License](#-license)

---

## 💡 Key Features

*   **AI-Powered OCR:** Extracts text from images on any webpage using Gemini AI.
*   **Real-time TTS:** Reads extracted text aloud, enhancing accessibility.
*   **Browser Integration:** Seamlessly works within Chrome, Firefox, and other Chromium-based browsers.
*   **User-Friendly Interface:** Intuitive controls for easy operation.
*   **Accessibility Focused:** Designed to assist users with visual impairments or those who prefer auditory information.

---

## ⚙️ Technology Stack

*   **Language:** TypeScript 6.x (Strict Mode Enabled)
*   **Bundler/Build Tool:** Vite 7.x (Rolldown)
*   **UI Framework:** TailwindCSS v3.x (Utility-First CSS)
*   **Browser Extension Framework:** WXT (Web Extension Tooling)
*   **AI Model:** Google Gemini API (Gemini Pro)
*   **Linting/Formatting:** Biome (Fast, All-in-One)
*   **Testing:** Vitest (Unit Testing), Playwright (End-to-End Testing)
*   **Architecture:** Feature-Sliced Design (FSD)

---

## 🤖 AI Agent Directives

<details>
<summary>View Agent Directives</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**. This repository, `WebVision-AI-Image-Text-Extractor-Browser-Extension`, is a TypeScript-based browser extension.

*   **PRIMARY SCENARIO A: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 6.x** (Strict Mode Enabled). Key tools include **Vite 7** (using Rolldown for bundling), **TailwindCSS v3.x** for styling, and **WXT (Web Extension Tooling)** for streamlined browser extension development.
    *   **State Management:** Adheres to standardized state management patterns, likely leveraging Signals or context APIs within the chosen framework.
    *   **Architecture:** Employs **Feature-Sliced Design (FSD)** to ensure maintainable, scalable, and decoupled code structure for the browser extension.
    *   **AI Integration:** Integrates with **Google Gemini API** (`gemini-3-pro` by default). Prioritize modular design, clear API contracts, and robust error handling for all AI model interactions.
    *   **Testing:** Utilizes **Vitest** for comprehensive unit testing and **Playwright** for reliable end-to-end testing of extension functionality across different browsers.

*   **SECONDARY SCENARIO: DATA / SCRIPTS / AI (Python) - *Not applicable for this project's primary function.***
    *   **Stack:** Python 3.10+ with uv, Ruff, Pytest.
    *   **Architecture:** Modular Monolith or Microservices.
    *   **CLI Framework:** Click.

---

## 4. CORE DEVELOPMENT MANDATES
*   **SOLID Principles:** Ensure adherence to Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion principles in all code.
*   **DRY (Don't Repeat Yourself):** Eliminate redundant code through abstraction and reusable components.
*   **YAGNI (You Ain't Gonna Need It):** Implement only necessary features; avoid premature complexity.
*   **KISS (Keep It Simple, Stupid):** Favor straightforward solutions.
*   **Security by Design:** Proactively identify and mitigate potential security vulnerabilities. Always sanitize inputs, validate outputs, and handle secrets securely.
*   **Performance Optimization:** Prioritize efficient algorithms and resource management, especially crucial for browser extensions.
*   **Accessibility (A11y):** Ensure the extension is usable by people with disabilities, following WCAG guidelines where applicable.

---

## 5. TESTING & VERIFICATION PROTOCOL
*   **Unit Testing:** All core logic, utility functions, and component behaviors must be covered by **Vitest** unit tests. Aim for a minimum of **90% code coverage**.
*   **Integration Testing:** Verify interactions between different modules and services.
*   **End-to-End (E2E) Testing:** Use **Playwright** to simulate real user interactions within browser environments, ensuring the extension functions correctly across target browsers (Chrome, Firefox).
*   **CI/CD Pipeline:** Automated execution of all tests, linting, and formatting checks upon every commit and pull request via GitHub Actions.

---

## 6. CODE QUALITY & STANDARDS
*   **Linter/Formatter:** **Biome** is the sole authority for code linting and formatting. All code must pass Biome checks without errors or warnings.
*   **TypeScript Strictness:** **`strict: true`** in `tsconfig.json` is mandatory. Enable all strict type-checking options.
*   **Commit Messages:** Follow the Conventional Commits specification (e.g., `feat: add new OCR capability`).
*   **Documentation:** Maintain comprehensive JSDoc comments for all public APIs, functions, and components.

---

## 7. CONTINUOUS INTEGRATION (CI) DIRECTIVE
*   **Provider:** GitHub Actions.
*   **Triggers:** `push` and `pull_request` events.
*   **Stages:** Install dependencies, run linters (Biome), run unit tests (Vitest), run E2E tests (Playwright), package extension (if applicable).
*   **Environment:** Utilize a consistent environment (e.g., Node.js LTS) across all CI runs.

---

## 8. SECURITY PROTOCOL
*   **Dependency Scanning:** Integrate tools like `npm audit` or Snyk into the CI pipeline to detect vulnerable dependencies.
*   **Secret Management:** **NEVER** hardcode API keys, tokens, or other secrets. Use environment variables managed securely (e.g., GitHub Secrets).
*   **Input Validation:** Rigorously validate all user inputs and data received from external sources.
*   **API Security:** Ensure secure communication with external APIs (e.g., Gemini API), using appropriate authentication and authorization mechanisms.
*   **Browser Extension Security:** Adhere to best practices for browser extension security, including content security policies (CSP) and minimizing required permissions.

---

## 9. REPOSITORY MANAGEMENT
*   **Branching Strategy:** Utilize a Gitflow-like branching model (e.g., `main`, `develop`, `feature/*`, `hotfix/*`).
*   **Pull Requests:** All code merged into `main` or `develop` must go through a Pull Request, requiring at least one approving review.
*   **Issue Tracking:** Use GitHub Issues for bug reports, feature requests, and task management.

</details>

---

## 🛠️ Development Setup

1.  **Clone the Repository:**
    bash
    git clone https://github.com/chirag127/WebVision-AI-Image-Text-Extractor-Browser-Extension.git
    cd WebVision-AI-Image-Text-Extractor-Browser-Extension
    

2.  **Install Dependencies:**
    *   Ensure you have Node.js (v18+) and npm/yarn/pnpm installed.
    *   This project uses `npm` and `vite`.
    bash
    npm install
    

3.  **Set Up Environment Variables:**
    *   Create a `.env` file in the root directory.
    *   Add your Gemini API key:
    env
    VITE_GEMINI_API_KEY=YOUR_GEMINI_API_KEY
    
    *   **Note:** This `.env` file should NOT be committed to version control. Use `.env.example` as a template.

4.  **Run Development Server:**
    bash
    npm run dev
    
    *   This command will build the extension in development mode and typically provide instructions on how to load it into your browser.

---

## ✅ Scripts

| Script              | Description                                                     |
| :------------------ | :-------------------------------------------------------------- |
| `npm run dev`       | Starts the development server and enables hot module replacement. |
| `npm run build`     | Builds the production-ready extension for deployment.           |
| `npm run lint`      | Runs Biome to check and format code.                            |
| `npm run test`      | Executes all Vitest unit tests.                                 |
| `npm run test:e2e`  | Runs Playwright end-to-end tests.                              |
| `npm run coverage`  | Generates code coverage reports.                                |

---

## 🛡️ Principles & Standards

*   **SOLID Principles:** Applied rigorously for maintainable and scalable code.
*   **DRY (Don't Repeat Yourself):** Maximizing code reusability.
*   **YAGNI (You Ain't Gonna Need It):** Focused implementation on current needs.
*   **KISS (Keep It Simple, Stupid):** Favoring straightforward solutions.
*   **Security by Design:** Proactive vulnerability mitigation and secure coding practices.
*   **Performance Optimization:** Ensuring the extension is lightweight and efficient.
*   **Accessibility (A11y):** Commitment to WCAG guidelines for inclusive design.

---

## 🤝 Contributing

Contributions are welcome! Please refer to the detailed guidelines in the `CONTRIBUTING.md` file.

---

## ⚖️ License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**. See the `LICENSE` file for more details.
