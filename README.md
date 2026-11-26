<div align="center">

# Ullas JS

**Software engineer · Kollam, India**

I build local-first desktop apps and the tooling around them.

[Portfolio](https://ullasjs.vercel.app) · [LinkedIn](https://www.linkedin.com/in/ullas-js-7694391b2) · Open to new roles

</div>

<br>

## Featured: QluePrint

[![Latest release](https://img.shields.io/github/v/release/u-ninja/qlueprint?style=flat-square&label=release)](https://github.com/u-ninja/qlueprint/releases/latest)
![Platforms](https://img.shields.io/badge/macOS%20%C2%B7%20Windows%20%C2%B7%20Linux-444?style=flat-square)
![License](https://img.shields.io/badge/source--available-PolyForm%20Shield-444?style=flat-square)

A local-first desktop workspace for PostgreSQL, MySQL, MariaDB, SQL Server, Azure SQL, Fabric and SQLite: write and run SQL, browse and edit data, and see a schema as a graph. No account, no cloud, no telemetry.

<p align="center">
  <img src="https://raw.githubusercontent.com/u-ninja/qlueprint/HEAD/docs/assets/screenshot-query.png" width="49%" alt="Writing and running SQL in QluePrint">
  <img src="https://raw.githubusercontent.com/u-ninja/qlueprint/HEAD/docs/assets/screenshot-table-edits.png" width="49%" alt="Editing a table, with staged changes in the Changes panel">
</p>

What's under the hood:

- **Rust core, React UI.** Tauri 2 shell; sqlx for PostgreSQL, MySQL and SQLite, and a patched Tiberius for SQL Server. Typed end to end, with generated bindings between Rust and TypeScript.
- **Edits are staged, not fired.** Cell and schema changes wait in a Changes panel as the exact SQL that will run, and apply only when confirmed.
- **Credentials stay in the OS keychain.** Microsoft Entra sign-in for Azure SQL and Fabric. A hash-chained audit log makes tampering detectable.
- **Local servers in a click.** It can start a PostgreSQL or MySQL container for you through Docker.
- **Shipped like a product.** Signed auto-updates, installers for three platforms built by GitHub Actions, and a changelog shown inside the app after each update.

<br>

## Also

| Project | What it is |
| --- | --- |
| [**ClipForge**](https://github.com/u-ninja/clip-forge) | A local-first, AI-assisted video production desktop app: Tauri shell, Fastify API, Python worker, SQLite with Drizzle. In early development. |
| [**agent-team-setup**](https://github.com/u-ninja/agent-team-setup) | An open-source Claude Code skill that sets up a team of specialist agents for a project and audits it as the project grows. |

<br>

## How I work

- **Local-first.** Your data stays on your machine unless you choose otherwise.
- **Small, frequent releases.** QluePrint has shipped a numbered release every few days, each with notes written for the person updating.
- **Reviewable changes.** Commits say what is pending and what comes next, so the log works as a progress tracker.
- **Working with Claude Code.** I use it daily, with a team of specialist agents per area of the codebase, and I open-sourced the setup.

<br>

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-444?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-444?style=flat-square&logo=react&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-444?style=flat-square&logo=rust&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-444?style=flat-square&logo=tauri&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-444?style=flat-square&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-444?style=flat-square&logo=fastify&logoColor=white)
![Python](https://img.shields.io/badge/Python-444?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-444?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-444?style=flat-square&logo=sqlite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-444?style=flat-square&logo=tailwindcss&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-444?style=flat-square&logo=githubactions&logoColor=white)
