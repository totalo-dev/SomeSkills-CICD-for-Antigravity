# SomeSkills CI/CD for Antigravity

[![CI/CD](https://img.shields.io/badge/CI%2FCD-Antigravity-blue)](https://github.com/totalo-dev/SomeSkills-CICD-for-Antigravity)

**CI/CD Antigravity 2** is a comprehensive plugin containing a set of orchestrating skills for advanced CI/CD automation, Code Quality, Deployment, and Observability within the Antigravity ecosystem.

## 🚀 Features & Skills Included

This plugin bundles various specialized skills designed to streamline the software development lifecycle:

- **AI Code Reviewer** (`ai-code-reviewer`): Advanced automated reviewer. Analyzes PRs for logical bugs, suggests improvements, and predicts deployment risks.
- **Artifact Manager** (`artifact-manager`): Manages build artifacts by versioning, storing them in registries/local directories, and cleaning up old builds.
- **Build Engine** (`build-engine`): Compiles applications, generates static bundles, and builds versioned Docker images.
- **Code Quality Guard** (`code-quality-guard`): Code policing. Enforces automatic linting, formatting (Prettier/Black), static analysis, and architectural rules.
- **Deploy Controller** (`deploy-controller`): Executes deployments to staging or production (blue/green), waiting for manual approvals when configured.
- **Notification Hub** (`notification-hub`): Communicates pipeline statuses (success, failure, deployment approvals) via Slack, Discord, or Email.
- **Observability Monitoring** (`observability-monitoring`): Manages centralized logs, performance metrics, and latency/error alerts in live applications.
- **Pipeline Router** (`pipeline-router`): The brain of CI/CD. Decides the order of skills, parallelizes tasks, skips unnecessary steps, and adapts the pipeline.
- **Rollback Engine** (`rollback-engine`): Detects post-deployment failures and automatically reverts the application to its last stable state.
- **Security Scanner** (`security-scanner`): DevSecOps skill. Scans for vulnerable dependencies, detects secrets (tokens/keys), and blocks insecure builds.
- **Test Orchestrator** (`test-orchestrator`): Centralizes and executes tests (Unit, Integration, E2E), optimizing execution time through parallelization.
- **Smart Trigger** (`trigger-inteligente`): Decides when the CI/CD pipeline should run. Detects pushes, PRs, tags, ignores non-impactful commits, and prioritizes branches.

## 🛠️ Usage

Once installed as an Antigravity plugin, these skills act autonomously or when directly invoked by the agent to automate CI/CD workflows dynamically.

## 📝 License

This project is open-source and available under the MIT License.
