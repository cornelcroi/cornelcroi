**20+ years of shipping software. The last few, shipping with AI.**

7 years at AWS as a Solutions Architect, building GenAI prototypes with customers across EMEA from the early days of LLMs, when Claude 3 was the new model. Now Staff GenAI Solutions Architect at Betclic and co-founder of two travel products in production. Along the way: a 7k-star agent orchestration framework and a family of MCP servers.

A few years of building with LLMs taught me three things. Most problems still want a query, a rule or a cron job, not a prompt. When a model does belong, the pattern matters more than the prompt: an agent that sees the data but never writes the reply, a pipeline that extracts facts before it narrates, a second model as reviewer instead of author. And a model is a fast pair of hands, not an architect. It writes code, docs and tests under my direction, and nothing I can't explain gets shipped.

I keep trying new patterns and write up the ones that hold: the [librarian pattern](https://dev.to/cornelcroi/the-librarian-pattern-how-i-keep-my-ai-coding-assistant-from-breaking-my-app-5396), which keeps an AI coding assistant from breaking my app, and [place extraction](https://dev.to/cornelcroi/you-just-write-the-places-find-themselves-2f2a), where the model reads and never invents. Latest experiment: on-device agent orchestration in Swift.

## 🚀 Live Products

Two travel products for the two halves of a trip: StreetLens while you're there, Back From My Trip once you're back.

| Product | What it does | Role |
|---------|--------------|------|
| 🌍 **[StreetLens](https://streetlensapp.com)** | Hear the story of the places around you, in your language. 6 cities, 8 languages, GPS-triggered narration. No account, no ads, pay per place. Every story is written by an LLM pipeline from extracted, source-tagged facts, validated against them, repaired or dropped. A new city in days. [streetlensapp.com](https://streetlensapp.com) · [App Store](https://apps.apple.com/app/id6756893250) | Co-founder |
| 🧳 **[Back From My Trip](https://www.backfrommytrip.com)** | Travel community where real travellers write trip reports that end with one honest question: would I go back? No star ratings. Behind the scenes an LLM pipeline moderates reports, extracts the places you mention and verifies photos. AI assists, never invents. [backfrommytrip.com](https://www.backfrommytrip.com) | Co-founder |

## 🤖 Open Source

| Project | What it is | Role |
|---------|------------|------|
| 🧠 **[Agent Squad](https://github.com/2fastlabs/agent-squad)** | Lightweight multi-agent orchestration framework. Python, TypeScript and Swift. Includes [GroundedAgent](https://2fastlabs.github.io/agent-squad/agents/built-in/grounded-agent): the agent that calls the tools never writes the reply. 7k⭐, formerly at AWS Labs. [NPM](https://www.npmjs.com/package/agent-squad) · [PyPI](https://pypi.org/project/agent-squad/) | Co-author |
| 🧩 **[Context Lens](https://github.com/cornelcroi/context-lens)** | MCP server for semantic search over local files and GitHub repositories. Think of it as SQLite for AI embeddings. | Author |
| 📊 **[Data Lens](https://github.com/cornelcroi/data-lens)** | MCP server to ask questions about spreadsheets in plain English. Excel, CSV, Parquet, powered by DuckDB. | Author |
| 🗣️ **[Ask James](https://github.com/cornelcroi/ask-james)** | MCP server that gets a second opinion from another LLM inside your assistant. | Author |
| ☁️ **[CloudFront Hosting Toolkit](https://github.com/awslabs/cloudfront-hosting-toolkit)** | CLI to deploy fast and secure frontends on Amazon CloudFront. [NPM](https://www.npmjs.com/package/@aws/cloudfront-hosting-toolkit) | Main maintainer |

## ✍️ Writing

| Date         | Title | Platform |
|--------------|-------|----------|
| 07 SEP 2026  | [You just write. The places find themselves.](https://dev.to/cornelcroi/you-just-write-the-places-find-themselves-2f2a) | dev.to |
| 26 AUG 2026  | [The Librarian Pattern: How I Keep My AI Coding Assistant from Breaking My App](https://dev.to/cornelcroi/the-librarian-pattern-how-i-keep-my-ai-coding-assistant-from-breaking-my-app-5396) | dev.to |
| 12 NOV 2025  | [Context-Lens: A Serverless, Open-Source MCP Server for AI Document Understanding](https://medium.com/@cornelcroi/how-i-built-context-lens-a-serverless-open-source-mcp-server-for-ai-document-understanding-ca375557a8fb) | Medium |
| 28 NOV 2024  | [Unlock Bedrock InvokeInlineAgent API's Hidden Potential with Multi-Agent Orchestrator](https://community.aws/content/2pTsHrYPqvAbJBl9ht1XxPOSPjR/unlock-bedrock-invokeinlineagent-api-s-hidden-potential-with-multi-agent-orchestrator) | community.aws |
| 12 SEP 2024  | [Beyond Auto-Replies: Building an AI-Powered E-commerce Support System](https://community.aws/content/2lq6cYYwTYGc7S3Zmz28xZoQNQj/beyond-auto-replies-building-an-ai-powered-e-commerce-support-system) | community.aws |
| 04 JUN 2024  | [Introducing CloudFront Hosting Toolkit](https://aws.amazon.com/blogs/networking-and-content-delivery/introducing-cloudfront-hosting-toolkit/) | AWS Blog |
| 10 JAN 2023  | [How DAZN Uses AWS Step Functions to Orchestrate Event-Based Video Streaming at Scale](https://aws.amazon.com/blogs/media/how-dazn-uses-aws-step-functions-to-orchestrate-event-based-video-streaming-at-scale/) | AWS Blog |

<details>
<summary>☁️ Earlier work at AWS</summary>

<br>

- **[Food Analyzer App](https://github.com/aws-samples/serverless-genai-food-analyzer-app)** — GenAI nutrition app for shopping and recipes. Built at an AWS hackathon, demoed at AWS Summits worldwide. Co-creator.
- **[A/B Testing at the Edge](https://github.com/aws-samples/ab-testing-at-edge)** — A/B testing on Amazon CloudFront for personalized content at scale. Owner and maintainer. [Workshop](https://catalog.us-east-1.prod.workshops.aws/workshops/e507820e-bd46-421f-b417-107cd608a3b2/en-US)
- **[Secure Media Delivery at the Edge](https://github.com/aws-solutions/secure-media-delivery-at-the-edge-on-aws)** — Protects premium video delivered through CloudFront. Sole coder, now maintained by the AWS Solutions team.
- **[Scaling cost effective architectures](https://catalog.us-east-1.prod.workshops.aws/workshops/f238037c-8f0b-446e-9c15-ebcc4908901a/en-US)** — Workshop.

</details>

---

<p align="center">
  <i>Always building.</i>
  <br>
  <i>If you're solving a real problem with AI and less code, reach out.</i>
  <br><br>
  <a href="https://www.linkedin.com/in/corneliucroitoru" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=Linkedin&logoColor=white" alt="LinkedIn"></a>
</p>
