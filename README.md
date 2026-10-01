# CodeGuard AI

### Own and customize your AI code-review workflow.

CodeGuard AI is a self-hosted AI code reviewer for GitHub Pull Requests, built with Java 17+ and Spring Boot.

Instead of relying only on a hosted code-review service, CodeGuard AI provides a customizable foundation for building and running your own AI-assisted review workflow.

Connect GitHub, choose your AI provider, and analyze Pull Requests for:

- 🐛 Bugs and logic issues
- 🔐 Security issues
- ⚡ Performance problems
- ✅ Best-practice violations

### Why CodeGuard AI?

CodeGuard AI is designed for developers who want control over their review workflow.

You can:

- Run it on your own infrastructure
- Choose OpenAI, Google Gemini, or Ollama
- Customize AI prompts and review instructions
- Modify the review logic
- Extend the GitHub integration
- Customize the dashboard and workflow
- Build additional developer-tool features on top of it

**Self-hosted. Customizable. Multi-provider. Built with Spring Boot.**

> The public repository is a showcase. The complete application source code is distributed separately.

## 🚀 Features

- 🤖 AI-powered GitHub Pull Request reviews
- 🐛 Bug and logic issue detection
- 🔐 Security issue detection
- ⚡ Performance analysis
- ✅ Best-practice checks
- 📊 Code quality scoring
- ⚠️ Risk assessment
- 🎯 AI confidence scoring
- 💬 Automatic GitHub review comments
- 🔄 Automatic reviews through GitHub webhooks
- 📝 Manual Pull Request reviews
- 📚 Review history
- 📈 Review trend tracking
- 📄 Markdown export
- 📑 PDF export
- 🌙 Light and dark mode
- 🔌 Multiple AI provider support


## 🧠 Supported AI Providers

CodeGuard AI supports multiple AI providers:

- OpenAI
- Google Gemini
- Ollama

The AI provider can be changed through configuration without changing the core review workflow.

This makes it possible to use cloud-based models or a locally running AI provider depending on your requirements.



## 🔄 How It Works

GitHub Pull Request
        ↓
GitHub Webhook
        ↓
CodeGuard AI
        ↓
Fetch PR Changes
        ↓
AI Analysis
        ↓
Security / Bug / Performance Review
        ↓
Quality & Risk Assessment
        ↓
GitHub Review Comment

                    GitHub
                       │
                       │ Pull Request
                       ▼
              GitHub Webhook
                       │
                       ▼
             ┌──────────────────┐
             │   CodeGuard AI   │
             │   Spring Boot    │
             └────────┬─────────┘
                      │
              Fetch PR Changes
                      │
                      ▼
             AI Review Service
                      │
          ┌───────────┼───────────┐
          ▼           ▼           ▼
       OpenAI      Gemini       Ollama
          │           │           │
          └───────────┼───────────┘
                      ▼
              Structured Findings
                      │
          ┌───────────┼───────────┐
          ▼           ▼           ▼
        Bugs      Security    Performance
          │           │           │
          └───────────┼───────────┘
                      ▼
              Quality / Risk Score
                      │
             ┌────────┴────────┐
             ▼                 ▼
        Dashboard       GitHub Review

📊 Review Results

A CodeGuard AI review can provide information such as:

Quality Score: 8/10
AI Confidence: 90%
Critical Issues: 0
Suggestions: 2
Risk Level: LOW

Findings can be categorized into areas such as:

Bugs
Security
Performance
Best Practices

The review results are intended to assist developers during code review and do not replace human review.

🖥️ Screenshots
Dashboard
![CodeGuard AI Dashboard](./Screenshot%20%28797%29.png)

AI Code Review Result
![CodeGuard AI Review Result](./Screenshot%20%28802%29.png)

Findings
![CodeGuard AI Findings](./Screenshot%20%28803%29.png)

Dark Mode
![CodeGuard AI Dark Mode](./Screenshot%20%28795%29.png)

🛠️ Technology Stack
Backend
Java 17+
Spring Boot
Spring Security
REST APIs
Maven
GitHub Integration
GitHub REST API
GitHub Pull Requests
GitHub Webhooks
GitHub review comments
AI
OpenAI
Google Gemini
Ollama
Frontend
HTML
CSS
Vanilla JavaScript
🔐 Self-Hosted & Private

CodeGuard AI is designed to run in your own environment.

Your GitHub credentials and AI provider credentials can remain under your control.

The application can work with repositories that the configured GitHub token has permission to access, including private repositories when the required permissions are configured.

🎯 Who Is It For?

CodeGuard AI is designed for:

Java developers
Spring Boot developers
Backend developers
Solo developers
Small development teams
Freelancers
Developers building internal developer tools
Developers experimenting with AI-assisted development workflows
💡 Why Build Your Own AI Code Reviewer?

Using a customizable source-code foundation gives developers the ability to modify the review workflow according to their own requirements.

You can customize areas such as:

AI prompts
Review categories
Risk assessment
Quality scoring
AI provider
GitHub integration
Dashboard
Review workflow
Authentication
Additional developer tools
📦 Source Code

The complete CodeGuard AI source code is available as a separate commercial source-code package.

The package includes:

Complete Spring Boot source code
Installation guide
User manual
API documentation
Architecture documentation
Database schema
SQL database script
Postman collection
Environment configuration guide
Sample repository guide
Changelog
License
Build. Customize. Self-host.

👉 Get CodeGuard AI Source Code - https://javacoder716.gumroad.com/l/codeguard-ai

⚠️ Requirements

The source-code project requires:

Java 17+
Maven 3.8+
GitHub Personal Access Token
OpenAI, Gemini, or Ollama
A GitHub repository / Pull Request accessible by the configured token

Detailed setup instructions are included with the source-code package.

🔗 Links

Source Code:
https://javacoder716.gumroad.com/l/codeguard-ai

GitHub Showcase:
https://github.com/Sweety717/CodeGuard-AI

Built by IsabiTech

📄 License

This public repository is a showcase/marketing repository for CodeGuard AI.

The complete application source code is distributed separately under a commercial license.

Please refer to the license included with the commercial source-code package for usage and redistribution terms.
