<div align="center">

<img src="./assets/command-deck.png" alt="CHEVCELLIOS Command Deck — automatic system initialization" width="100%" />

### `SOFTWARE ENGINEERING` · `CYBERSECURITY` · `CREATIVE TECHNOLOGY`

[![Explore systems](https://img.shields.io/badge/EXPLORE-SYSTEMS-22E6E3?style=for-the-badge&logo=github&logoColor=050811&labelColor=0A1020)](https://github.com/ChevCellios?tab=repositories)
[![Live deployment](https://img.shields.io/badge/LAUNCH-PETABIT-38F59D?style=for-the-badge&logo=rocket&logoColor=050811&labelColor=0A1020)](https://petabit-production.up.railway.app/)
[![NexusOps deployment](https://img.shields.io/badge/LAUNCH-NEXUSOPS-A277FF?style=for-the-badge&logo=rocket&logoColor=050811&labelColor=0A1020)](https://nexusopsvoiceworker-production.up.railway.app/)

</div>

## `> OPERATOR PROFILE`

Developer building focused applications, secure web systems, automation, and visual experiments. I turn complex ideas into software that is clear, useful, tested, and maintainable.

I'm Dominik Tupek, a developer in Zagreb building practical experience in application security and software delivery. My background in technical and field work shapes how I approach engineering: understand the system, troubleshoot methodically, and verify the result.

I have completed ASP.NET Core Developer training and am currently studying toward ISC2 Certified in Cybersecurity (CC). My direction is Application Security, Blue Team, and Security Engineering, with hands-on learning through my own applications and Linux environments.

## `> FEATURED APPLICATIONS`

| Project | What I am building | Explore |
| --- | --- | --- |
| **Petabit** | Multilingual ASP.NET Core MVC application with ISS tracking, application security controls, and production checks. | [Source](https://github.com/ChevCellios/Petabit) · [Production](https://petabit-production.up.railway.app/) |
| **NexusOps** | Operations portal and AI-assisted voice service using .NET, PostgreSQL, Twilio, and OpenAI Realtime. Active development. | [Source](https://github.com/ChevCellios/NexusOps.VoiceWorker) · [Production](https://nexusopsvoiceworker-production.up.railway.app/) · [Public health endpoint](https://nexusopsvoiceworker-production.up.railway.app/health) |

NexusOps portal access depends on the configured authentication and roles; its public health endpoint provides a lightweight service check.

## `> SECURITY IN PRACTICE`

I develop my security skills by implementing controls, testing behavior, and reviewing automated findings in my projects.

- **Application protection:** Petabit uses HTTPS/HSTS, Content Security Policy with nonces, antiforgery protection, and rate limiting.
- **Identity and access:** NexusOps implements backend tenant and role checks, Twilio callback signature validation, and production configuration checks that fail closed.
- **Code and dependency analysis:** both repositories configure CodeQL for C# and NuGet vulnerability checks, including transitive dependencies.
- **Container security:** NexusOps CI builds its Docker image and runs Trivy with HIGH and CRITICAL findings configured to fail the scan step.

These are concrete engineering practices in my projects, alongside continued study of OWASP Top 10, networking, and defensive security.

## `> AUTOMATION & DELIVERY`

| Area | Repository configuration |
| --- | --- |
| **Continuous integration** | GitHub Actions restores dependencies, builds Release configurations, runs tests, and verifies Docker builds in both projects. |
| **Dependabot** | Weekly NuGet and GitHub Actions updates in both repositories; NexusOps also checks Docker dependencies. |
| **Patch update automation** | Petabit groups patch updates and has a workflow that requests squash auto-merge for Dependabot patch PRs. Actual merging depends on repository rules and auto-merge settings. |
| **Security workflows** | CodeQL runs on pushes, pull requests, and a weekly schedule. NuGet audits check for vulnerable dependencies. |
| **Production checks** | Petabit's smoke workflow checks its home page, readiness endpoint, and ISS tracker after pushes to `master`, or on manual runs. A separate weekly workflow checks curated ISS data freshness. |
| **Delivery** | Both projects have Railway production deployments. NexusOps's GitHub Actions workflow validates the application; deployment is handled separately from that CI workflow. |

[Petabit CI](https://github.com/ChevCellios/Petabit/actions/workflows/ci.yml) · [Petabit Security](https://github.com/ChevCellios/Petabit/actions/workflows/security.yml) · [NexusOps CI](https://github.com/ChevCellios/NexusOps.VoiceWorker/actions/workflows/ci.yml) · [NexusOps CodeQL](https://github.com/ChevCellios/NexusOps.VoiceWorker/actions/workflows/codeql.yml)

## `> LINUX WORKBENCH`

I use **Kali Linux** and **Parrot OS** as environments for learning, security tooling, and practical lab work. Linux is also part of how I build familiarity with the terminal, networking, permissions, and system administration.

Respect for **Linux Mint**: I value a lean, practical setup that gives older or lower-spec computers a useful second life. Keeping the desktop and background services lightweight matters to me as much as the tools I install.

## `> MORE PROJECTS & TOOLS`

<img src="./assets/deployed-systems.svg" alt="Featured systems: Petabit, JEKA AOPS and Visual Motivation" width="100%" />

<div align="center">

[![Petabit source](https://img.shields.io/badge/PETABIT-SOURCE-22E6E3?style=flat-square&logo=github&labelColor=0A1020)](https://github.com/ChevCellios/Petabit)
[![JEKA AOPS source](https://img.shields.io/badge/JEKA_AOPS-SOURCE-A277FF?style=flat-square&logo=github&labelColor=0A1020)](https://github.com/ChevCellios/jeka-aops)
[![Visual Motivation source](https://img.shields.io/badge/VISUAL_MOTIVATION-SOURCE-38F59D?style=flat-square&logo=github&labelColor=0A1020)](https://github.com/ChevCellios/VisualMotivation)

</div>

<img src="./assets/capability-matrix.svg" alt="Capability matrix covering engineering, interfaces, data, operations and security" width="100%" />

<div align="center">

[![Languages and tools](https://skillicons.dev/icons?i=cs,dotnet,ts,js,html,css,react,nodejs,python,postgres,docker,git,github,vscode&theme=dark&perline=14)](https://skillicons.dev)

</div>

<img src="./assets/delivery-protocol.svg" alt="Delivery protocol: understand, design, build, verify and ship" width="100%" />

<div align="center">

### `BUILD CLEARLY · LEARN CONTINUOUSLY · LEAVE THE SYSTEM BETTER`

</div>
