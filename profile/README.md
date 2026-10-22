<p align="center">
  <a href="https://netgrif.com/">
    <img src="https://netgrif.com/wp-content/uploads/2023/05/svgx-netgrif-full-grey-2-2.svg" alt="NETGRIF" width="260">
  </a>
</p>

<h1 align="center">From business process to working application.</h1>

<p align="center">
  Design workflows, forms, data and permissions in one executable model.<br>
  Run them with Netgrif Application Engine and build applications around them.
</p>

<p align="center">
  <a href="https://builder.netgrif.cloud/modeler"><strong>Try the Builder</strong></a>
  ·
  <a href="https://etask.netgrif.cloud/"><strong>Live Engine</strong></a>
  ·
  <a href="https://platform.netgrif.cloud/"><strong>Documentation</strong></a>
  ·
  <a href="https://platform.netgrif.cloud/guides/"><strong>Tutorials and Guides</strong></a>
</p>

---

## What is Netgrif?

**Netgrif is a platform for building process-driven applications.** You model
the process once and the platform runs it. You do not have to build workflow,
form and task-management mechanisms from scratch.

At its core is [Petriflow](https://petriflow.org/#/), a workflow language for
modeling and executing process-centric objects based on Petri nets. A single
Petriflow model describes:

- **Processes and workflows**: how work moves between tasks and states.
- **Data and forms**: the information users work with.
- **Roles and permissions**: who can perform which tasks.
- **Actions**: application-specific behavior attached to the process.

A Petriflow model is not documentation/specification that developers translate into code.
Netgrif executes it directly. The platform handles process execution, case and
task management, APIs and reusable frontend components. You stay in control of
the application-specific logic and the user experience.

**Model the process. Run it. Build on top of it.**

<details>
<summary><strong>What can you build with Netgrif?</strong></summary>

### Use cases

Netgrif fits applications where people, data and structured workflows meet.

| Use case                         | Examples                                               |
| -------------------------------- | ------------------------------------------------------ |
| **Approval workflows**           | Purchase requests, leave approvals, expense reviews    |
| **Case management**              | Service requests, complaints, internal cases           |
| **Business operations**          | Onboarding, document processing, multi-step procedures |
| **Internal applications**        | Task-driven tools with forms, roles and permissions    |
| **Custom workflow applications** | Domain-specific systems built with Java and Angular    |

### Why build with Netgrif?

- **The model is the application.** What you design is what runs, so there is
  no gap between the process diagram and the implementation.
- **Visual modeling with developer control.** Design processes in the Builder,
  then extend them with Petriflow actions and your own code.
- **Familiar technologies.** Java, Spring Boot, Angular and REST APIs.
- **Focus on what is unique.** Process execution, task lifecycle and data
  management are already there, so you do not have to rebuild them.

</details>

---

## The platform

| Project                                                                   | What it does                                                                |
| ------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| [**Application Builder**](https://github.com/netgrif/application-builder) | Design Petriflow processes, data, forms and roles visually in your browser. |
| [**Application Engine**](https://github.com/netgrif/application-engine)   | Run Petriflow models and manage processes, cases, tasks, users and data.    |
| [**Netgrif Components**](https://github.com/netgrif/components)           | Build Angular user interfaces connected to Netgrif Application Engine.      |

<details>
<summary><strong>How the pieces fit together</strong></summary>

```text
              APPLICATION BUILDER
             Visual process modeling
                       │
                       │ Export
                       ▼
                 PETRIFLOW MODEL
          Process + Data + Forms + Roles
                       │
                       │ Load
                       ▼
              APPLICATION ENGINE
              Java + Spring Boot
          Process execution and APIs
                       │
                       │ REST APIs
                       ▼
             FRONTEND APPLICATION
             Angular + Components
                       │
                       ▼
                      USERS
```

You design the process in the **Builder**. The result is a **Petriflow** model.
The **Application Engine** runs the model and manages its cases, tasks, users
and data. **Netgrif Components** help you build the Angular application your
users work with.

</details>

---

## Try it in your browser

You can explore Netgrif without installing anything.

1. Open the [Application Builder](https://builder.netgrif.cloud/).
2. Create a process and add data, forms, roles and actions.
3. Export the Petriflow model.

If you want to see the end-user side first, open the
[live engine](https://etask.netgrif.cloud/) and browse its processes, cases and tasks.

For guided examples, visit the [Netgrif Platform documentation](https://platform.netgrif.cloud/guides/).

---

## Build your own application

We are publishing the **Netgrif Community Edition** and the developer
tools you need to build and run your own process-driven applications. Start
from one of the starter repositories:

| Starter                                                                                             | Use it to                                                                                                                        |
| --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| [**nae-backend-application-starter**](https://github.com/netgrif/nae-backend-application-starter)   | Create a Java and Spring Boot backend powered by Netgrif Application Engine: your own logic, process execution and integrations. |
| [**nae-frontend-application-starter**](https://github.com/netgrif/nae-frontend-application-starter) | Create an Angular frontend for Netgrif processes, cases, tasks and data, customized with Netgrif Components and your own code.   |

<details>
<summary><strong>Typical development workflow</strong></summary>

1. Design the process in Application Builder.
2. Export the Petriflow model.
3. Set up the backend and frontend from the starter repositories.
4. Load the model into your Application Engine. See the
   [Application Engine Documentation](https://platform.netgrif.cloud/).
5. Extend and customize the application for your users.

Each starter repository has its own setup instructions and requirements.

</details>

---

## Learn and get help

- [**Getting Started**](https://netgrif.com/get-started/): an introduction to the platform.
- [**Petriflow Documentation**](https://petriflow.org/#/): language concepts, objects, actions and examples.
- [**Application Engine Documentation**](https://platform.netgrif.cloud/): technical documentation and APIs.
- [**Netgrif Academy**](https://platform.netgrif.cloud/guides/): tutorials, examples and learning materials.
- [**Discussions**](https://github.com/netgrif/application-engine/discussions): questions, ideas and community conversations.
- [**Issues**](https://github.com/netgrif/application-engine/issues): bug reports and technical problems.

Need a supported deployment or the Enterprise Edition?
[Contact Netgrif](https://netgrif.com/contact-us/).

---

<details>
<summary><strong>Licensing</strong></summary>

Netgrif Community Edition is published in the repositories of this organization.
Each project has its own license, including the **NETGRIF Community License**.
Check the license in each repository before you use, modify or deploy its software.

</details>

---

<p align="center">
  <strong>Start with a process. Turn it into an application.</strong>
</p>

<p align="center">
  <a href="https://builder.netgrif.cloud/modeler">Start building with Netgrif →</a>
</p>
