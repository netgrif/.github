<p align="center">
  <a href="https://netgrif.com/">
    <img src="https://netgrif.com/wp-content/uploads/2023/05/svgx-netgrif-full-grey-2-2.svg" alt="NETGRIF" width="260">
  </a>
</p>

<h1 align="center">Describe a business process. AI turns it into a running app.</h1>

<p align="center">
  Netgrif is the AI-native platform for process applications. Login, roles, forms, task lists,<br>
  the portal and the database already run. AI writes only the process.
</p>

<p align="center">
  <a href="https://github.com/netgrif/starter"><strong>Build with AI</strong></a>
  ·
  <a href="https://builder.netgrif.cloud/modeler"><strong>Try the Builder</strong></a>
  ·
  <a href="https://etask.netgrif.cloud/"><strong>Live Engine</strong></a>
  ·
  <a href="https://platform.netgrif.cloud/"><strong>Documentation</strong></a>
</p>

![One Petriflow model, built with Netgrif AI Code or in the Builder, runs in the engine and is used in the portal or through Netgrif AI Chat](media/demo.gif)

<sub>One Petriflow model: built with AI or by hand in the Builder, used by clicking in the portal or by asking Netgrif
AI Chat.</sub>

## What is Netgrif?

A platform for process-driven applications. The process is written in
[Petriflow](https://petriflow.org/#/), a language for object-centric processes based on Petri nets. One Petriflow
model holds the workflow, the data and forms, the roles and permissions, and the actions. The Netgrif Application
Engine runs it directly, so the model *is* the application.

That is why AI works well here. It does not generate a whole application for you to review and secure. It writes one
model that a person can read, the platform can check, and the engine runs as it is. AI is optional: the same process
can be modeled by hand in the Builder and used by clicking in the portal.

## Build your first app with AI

**Netgrif AI Code** is your AI coding assistant, prepared for Netgrif. Start it for free on your own machine:

1. **Start Netgrif.** Clone [**netgrif/starter**](https://github.com/netgrif/starter) and run `docker compose up -d`.
2. **Describe your business problem.** Open the folder in Claude Code, Codex, Cursor, GitHub Copilot or Gemini CLI and
   tell it what your business needs, or hand it a Word document you already have. It writes the process, checks it,
   and deploys it after your yes. Then work in the app at http://localhost:4200.

Step by step: [starter README](https://github.com/netgrif/starter#readme).

## Netgrif AI Suite <sub>beta</sub>

| | For | What it does |
|---|---|---|
| **Netgrif AI Code** | developers | Builds and changes Netgrif apps from your coding assistant. Free on your machine with the starter. |
| **Netgrif AI Chat** | people who use the apps | "What is waiting for me?", "Approve the one from ACME." Users work in the apps in plain language. |

The AI always acts as the signed-in person, with their roles and rights, and every change waits for their yes.
Shared portals with your company login (SSO) and AI Chat are part of the Enterprise edition:
[contact us](https://netgrif.com/contact-us/).

## The platform

| Project | What it does |
|---|---|
| [**Starter**](https://github.com/netgrif/starter) | Netgrif on your machine, ready for your AI assistant. |
| [**Application Builder**](https://github.com/netgrif/application-builder) | Model Petriflow processes, forms and roles visually in the browser. |
| [**Application Engine**](https://github.com/netgrif/application-engine) | Run Petriflow models: processes, cases, tasks, users and data. |
| [**Netgrif Components**](https://github.com/netgrif/components) | Build your own Angular frontend on the engine. |
| [**Petriflow**](https://github.com/petriflow/petriflow) | The process language: specification and Action API. |

Need your own Java backend or Angular frontend? Start from
[nae-backend-application-starter](https://github.com/netgrif/nae-backend-application-starter) and
[nae-frontend-application-starter](https://github.com/netgrif/nae-frontend-application-starter).

## Learn and get help

[Getting Started](https://netgrif.com/get-started/) ·
[Petriflow docs](https://petriflow.org/#/) ·
[Platform docs](https://platform.netgrif.cloud/) ·
[Netgrif Academy](https://platform.netgrif.cloud/guides/) ·
[Discussions](https://github.com/netgrif/application-engine/discussions) ·
[Issues](https://github.com/netgrif/application-engine/issues) ·
[Contact Netgrif](https://netgrif.com/contact-us/)

<sub>**Licence.** Netgrif Community Edition is source-available, not open source, under the NETGRIF Community License.
Its current version is free for development, testing and other non-production use; production needs a commercial
licence. Projects can use different licence versions, so check each repository. The Petriflow specification is open
source under Apache 2.0.</sub>
