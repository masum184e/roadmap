# GitHub Actions Must-Know Topics

## 1. Basics
  - What is GitHub Actions
  - Workflows, Jobs, and Steps
  - Runners (GitHub-hosted vs Self-hosted)
  - Triggers (events: `push`, `pull_request`, `schedule`, `workflow_dispatch`)

## 2. Workflow Files
  - YAML syntax basics
  - File location (`.github/workflows/`)
  - `on:` keyword (defining triggers)
  - `jobs:` keyword
  - `steps:` keyword

## 3. Actions
  - Using marketplace actions (`uses:`)
  - Writing custom actions
    - JavaScript actions
    - Docker container actions
  - Reusable workflows

## 4. Environment & Contexts
  - Environment variables (`env`)
  - Contexts (`github`, `runner`, `job`, `steps`, `secrets`)
  - Expressions (`${{ }}` syntax)
  - Matrix builds

## 5. Secrets & Security
  - Storing secrets in GitHub
  - Using secrets in workflows
  - Encrypted secrets vs environment variables
  - Managing permissions with `GITHUB_TOKEN`

## 6. Caching & Artifacts
  - Cache dependencies (npm, pip, etc.)
  - Uploading & downloading artifacts
  - Build and test artifact handling

## 7. Testing & CI/CD
  - Running tests automatically
  - Linting & formatting checks
  - Multi-environment testing (matrix)
  - Code coverage reports

## 8. Deployment
  - Deploying to cloud providers (AWS, Azure, GCP)
  - Deploying to Vercel/Netlify/Heroku
  - SSH & Docker deployment
  - GitHub Pages deployment

## 9. Optimization
  - Job concurrency & dependencies (`needs`)
  - Parallel jobs
  - Conditional steps (`if:`)
  - Reusable workflows & composite actions

## 10. Monitoring & Debugging
  - Logs & debugging with `ACTIONS_STEP_DEBUG`
  - Retrying failed jobs
  - Notifications (Slack, Discord, email)

## 11. Advanced Features
  - Scheduled workflows (`cron`)
  - Self-hosted runners setup
  - Caching Docker layers
  - Monorepo workflow strategies
  - Reusable workflows across repositories
