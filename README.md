CraveCoach – Homemade Meal & Nutrition Platform
A decentralized full-stack web application built on the Internet Computer Protocol (ICP) for exploring homemade meals, managing healthy food menus, and tracking nutritional preferences through a responsive TypeScript and React interface.


⚡ Features

Curated Homemade Menu: Browse wholesome homemade meal options with detailed nutritional breakdowns and portion insights.
Interactive Meal Filtering & Discovery: Quickly filter dishes based on dietary preferences, fitness goals, and meal categories.
Decentralized Backend Canisters: Powered by Internet Computer (icp.yaml) architecture for tamper-resistant, scalable state management and API execution.
Modular Workspace Architecture: Clean separation between frontend UI components and backend canister logic managed via pnpm workspaces.
Containerized & Automated Workflows: Includes Docker configuration (Dockerfile), automated build scripts (build.sh, deploy.sh), and CI/CD pipelines.


🛠️ Tech Stack
Frontend (/src/frontend)
Framework: React with TypeScript
Build Tool: Vite
Package Manager: pnpm (Monorepo / Workspace setup)

Backend & Infrastructure (/src/backend)
Platform: Internet Computer Protocol (ICP)
Configuration & Deployment: icp.yaml, caffeine.lock.json, Shell automation (build.sh, deploy.sh)
Containerization: Docker


📁 Repository Structure

cravecoach-homemade/
├── .github/                     # GitHub Actions & repository workflows
├── scripts/                     # Utility and automation scripts
├── src/
│   ├── frontend/                # React + TypeScript client application
│   └── backend/                 # Internet Computer backend canister logic
├── build.sh                     # Automated workspace build script
├── deploy.sh                    # Canister and application deployment script
├── Dockerfile                   # Container environment setup
├── icp.yaml                     # Internet Computer canister configuration
├── package.json                 # Root workspace scripts and metadata
├── pnpm-lock.yaml               # Deterministic dependency lockfile
├── pnpm-workspace.yaml          # Multi-package pnpm workspace definition
├── spec.md                      # Functional and architectural specifications
└── tsconfig.json                # Root TypeScript compiler configuration


🚀 Getting Started Locally

1. Clone the Repository
2. Install Workspace Dependencies
3. Build & Run Locally :: Running the Frontend Development Server


👤 Author

arikgoti – GitHub Profile
