🫁 Lung Cancer Detection Web Application

A modern web-based application built to assist in the visualization and detection of lung cancer. This project provides a fast, responsive user interface developed with Vite and TypeScript, featuring comprehensive testing and Docker support for seamless deployment.

## 🚀 Features

* **Modern UI:** Built with HTML, TypeScript, and modern styling utilities for a responsive experience.
* **Fast Development:** Powered by Vite for lightning-fast Hot Module Replacement (HMR).
* **Robust Testing:** Includes both unit testing with Vitest and End-to-End (E2E) testing with Playwright.
* **Containerized:** Easily deployable using the included `docker-compose.yml` configuration.
* **Strict Typing & Linting:** Enforced code quality with TypeScript and ESLint.

## 🛠️ Tech Stack

* **Language:** TypeScript, JavaScript, HTML
* **Build Tool:** [Vite](https://vitejs.dev/)
* **Package Manager:** Bun (via `bun.lock`) / npm
* **Styling:** Tailwind CSS (`tailwind.config.ts`, `postcss.config.js`)
* **Testing:** * Unit/Component: Vitest (`vitest.config.ts`)
  * E2E: Playwright (`playwright.config.ts`)
* **Deployment:** Docker & Docker Compose

## 📂 Project Configuration Structure

```text
Lung-Cancer-Detection/
│
├── index.html                 # Main entry point
├── package.json               # Project metadata and scripts
├── bun.lock & package-lock.json # Dependency lockfiles
├── docker-compose.yml         # Docker orchestration
├── vite.config.ts             # Vite bundler configuration
├── tailwind.config.ts         # Tailwind CSS styling configuration
├── eslint.config.js           # Linting rules
├── vitest.config.ts           # Unit testing configuration
├── playwright.config.ts       # E2E testing configuration
└── tsconfig.*.json            # TypeScript configurations
⚙️ Getting Started
Follow these steps to set up the project locally.

Prerequisites
Node.js (v18 or higher recommended)

Bun (Recommended, as bun.lock is present) or npm

Docker (Optional, for containerized execution)

Local Development
1. Clone the repository:

Bash
git clone [https://github.com/mansiym13-sketch/Lung-Cancer-Detection.git](https://github.com/mansiym13-sketch/Lung-Cancer-Detection.git)
cd Lung-Cancer-Detection
2. Install dependencies:
If using Bun:

Bash
bun install
(Alternatively, you can use npm install)

3. Start the development server:

Bash
bun run dev
The Vite development server will start, typically accessible at http://localhost:5173.

🐳 Running with Docker
To spin up the application in an isolated container environment using Docker Compose:

Bash
docker-compose up --build -d
This will build the image and run the container in detached mode.

🧪 Testing
This project employs a dual-testing strategy.

Run Unit Tests (Vitest):

Bash
bun run test
Run End-to-End Tests (Playwright):

Bash
# You may need to install Playwright browsers first: npx playwright install
bun run test:e2e  # Or the specific script defined in package.json
🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.
