# Contribution Guide: WebVision-AI-Image-Text-Extractor-Browser-Extension

As an Apex Technical Authority project, contributions to `WebVision-AI-Image-Text-Extractor-Browser-Extension` must adhere to the highest standards of code quality, architectural soundness, and future-proofing, consistent with the principles outlined in `AGENTS.md`.

## 1. Core Philosophy

We operate under the **Zero-Defect, High-Velocity, Future-Proof** mandate. All contributions are expected to enhance robustness, performance, and maintainability. We embrace the wisdom of **SOLID** principles, **DRY** coding, and strictly adhere to **YAGNI** (You Ain't Gonna Need It) until necessary.

## 2. Prerequisites & Development Environment

This repository utilizes a modern **TypeScript/Vite** stack for the Browser Extension architecture, ensuring strict typing and performance optimization.

Before contributing, ensure you have the following installed:

1.  **Node.js:** Version 20.x or higher (LTS recommended).
2.  **Git:** Version 2.30+.
3.  **Package Manager:** `npm` or `yarn` (we standardize on `npm` for workflow consistency).

### Setup Instructions

1.  **Fork and Clone:** Fork this repository and clone your fork locally.
    bash
    git clone https://github.com/chirag127/WebVision-AI-Image-Text-Extractor-Browser-Extension.git
    cd WebVision-AI-Image-Text-Extractor-Browser-Extension
    
2.  **Install Dependencies:** Use `npm` to install all required packages, including development dependencies.
    bash
    npm install
    
3.  **Compile & Run:** Run the development build to start the local development server or build process.
    bash
    npm run dev
    

## 3. Contribution Workflow

Follow these steps for any feature, fix, or documentation update:

1.  **Create a Branch:** Base your work on the latest `main` branch and create a descriptively named feature branch. Adhere to the [Conventional Commits specification](https://www.conventionalcommits.org/en/v1.0.0/):
    bash
    git checkout -b feat/short-description-of-change
    # OR
    git checkout -b fix/issue-number-fix-description
    
2.  **Make Changes:** Implement your changes. Ensure all new code is accompanied by appropriate tests.
3.  **Lint & Format Check:** Before committing, run the automated linter/formatter to ensure compliance with Apex standards.
    bash
    npm run lint
    npm run format
    
4.  **Commit:** Commit your changes using the Conventional Commit format (e.g., `feat: add new Gemini API error handler`).
5.  **Push:** Push your branch to your fork.
    bash
    git push origin feat/your-branch-name
    
6.  **Open Pull Request:** Open a Pull Request against `chirag127/WebVision-AI-Image-Text-Extractor-Browser-Extension:main`.

## 4. Pull Request (PR) Requirements

All Pull Requests **MUST** satisfy the following criteria before merging:

*   **Clarity:** The PR description must clearly articulate **What** was done, **Why** it was done, and **How** it was verified. Reference any related issues.
*   **CI Pass:** The Continuous Integration workflow (`.github/workflows/ci.yml`) must pass all checks (Build, Lint, Test).
*   **Testing:** New features must include comprehensive unit tests (Vitest) and/or integration tests (Playwright) to achieve or maintain high coverage (>85%).
*   **Documentation Update:** If the change impacts public APIs, architecture, or setup, update `README.md` and/or relevant documentation files.
*   **Agent Alignment:** Verify that the changes do not contradict the architectural patterns or toolchain definitions laid out in `AGENTS.md`.

## 5. Testing Strategy

We employ a multi-layered testing approach:

*   **Unit Tests (Vitest):** Mandatory for all core logic, utility functions, and API interaction handlers. Focus on mocking external dependencies like the Gemini API.
*   **E2E Tests (Playwright):** Required for critical user journeys, such as initiating OCR on an image and verifying TTS output playback.

## 6. Code of Conduct

This project adheres to a professional and respectful environment. By participating, you agree to abide by the **Contributor Covenant Code of Conduct**, which can be reviewed in `.github/CODE_OF_CONDUCT.md` (if present, otherwise standard guidelines apply).

*Thank you for helping to elevate this project to the Apex standard.*