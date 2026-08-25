# Hi, I'm Johan 👋

Software Testing student in Stockholm, developing toward Quality Engineering with a focus on test design, test automation, system quality and critical use of AI.

I build practical, reviewable projects where quality is demonstrated through testing, documented decisions, verification, measured results and known limitations.

My current main projects are Project Compass and Evidence Transcriber.

---

## What I focus on

- Quality Engineering: product risk, user flows, traceability and verification
- Test design: boundary values, equivalence partitioning, exploratory testing and regression
- Test automation: Playwright end-to-end testing and reliable CI execution
- API testing: HTTP/API verification with Postman and Newman
- Engineering foundations: TypeScript, Git/GitHub, CI/CD, data persistence and debugging
- AI-assisted QA: using AI for analysis and implementation support, with human review and verification
- Documentation and evidence: test results, technical decisions, limitations and reproducible project notes
---

## Featured projects

### Project Compass

[Repository](https://github.com/Zion8a/project-compass) · [Live demo](https://project-compass-seven.vercel.app/)

Project Compass is a project clarity and project management MVP built with Next.js and TypeScript. It explores how smaller projects can make responsibility, risks, decisions, traceability and current project health visible instead of reducing project work to task tracking alone.

For me, this is primarily a Quality Engineering project. I use it to develop product thinking, risk-based testing, regression testing, test automation and CI while evolving a real application in small, verifiable steps.

Current areas include:

* Multiple saved projects and active project handling
* Responsibility for tasks, risks and decisions
* Risk-to-task and decision-to-task traceability
* Project Health, Attention Needed and Recommended Next Step
* Status reporting and Markdown export
* Playwright end-to-end testing
* GitHub Actions CI
* Live deployment on Vercel

The current version stores project data locally in the browser using `localStorage`. It is not yet a multi-user application.

---

## Evidence Transcriber

[Repository](https://github.com/Zion8a/evidence-transcriber)

Evidence Transcriber is a Windows-first, local-first transcription project built around an evidence-oriented principle:

**preserve the source and raw model output before correcting or interpreting it.**

The project separates:

**Source / Original → Raw ASR Transcript → Edited Transcript → future AI Interpretation**

The current application provides a packaged Windows workflow from audio import to Swedish transcription, human editing, persistent storage, session reopening and TXT export.

The project is particularly focused on:

- Local speech recognition with whisper.cpp
- FFmpeg-based audio preprocessing
- Preservation of the original source
- Separation of raw and human-edited transcripts
- Segment timestamps
- Persistence and data integrity
- Failure and recovery behaviour
- Regression testing of provenance-critical behaviour
- Verification on the actual Windows target machine

The application is packaged as a Windows desktop application while retaining a local-first architecture.

This project gives me a practical environment for exploring both Quality Engineering and the additional quality problems that appear when AI becomes a system component.

---

### QA Career Journey

[Repository](https://github.com/Zion8a/qa-career-journey-v2)

This repository documents the earlier and foundational part of my development in software testing.

It contains practical work with:

* Test design
* Boundary value analysis and equivalence partitioning
* Bug reporting
* Exploratory testing
* API testing with Postman
* Newman CLI execution
* Playwright UI automation
* Negative scenarios and validation
* GitHub Actions CI
* Test documentation

I keep this repository as part of the portfolio because it shows progression from individual testing techniques toward broader Quality Engineering work.

---

## Supporting QA labs

These smaller repositories focus on specific techniques rather than complete products:

* [Playwright UI + CI](https://github.com/Zion8a/playwright-ci-starter) – browser automation, assertions, user flows and CI execution
* [API Testing with Postman/Newman](https://github.com/Zion8a/api-testing-newman-ci) – API verification, CLI execution and automated reporting
* [Test Techniques Demo](https://github.com/Zion8a/test-techniques-demo) – equivalence partitioning, boundary value analysis and automated examples
* [Java for Testers](https://github.com/Zion8a/java-for-testers) – earlier programming exercises connected to testing and automation fundamentals

---

## Quick review guide

If you only have a few minutes:

1. Start with **Project Compass** for my main product and Quality Engineering case.
2. Open **Evidence Transcriber** for my current work with local AI, provenance, data integrity and verification.
3. Review **QA Career Journey** to see the testing foundations and progression behind the larger projects.
4. Use the supporting QA labs for focused examples of Playwright, API testing and test design.

---

## Current tools and technologies

### Main engineering and QA work

* TypeScript
* Playwright
* Git / GitHub
* GitHub Actions
* Next.js
* Node.js

### API and test tooling

* Postman
* Newman

### Local AI and media processing

* whisper.cpp
* FFmpeg

### Earlier programming foundations

* Java
* JUnit

I treat tools as means to solve and verify problems rather than as portfolio goals in themselves.

---

## What this portfolio is intended to show

This portfolio documents my development from a software testing student toward broader Quality Engineering work.

The goal is not to present every exercise as a finished product or to suggest that I already know everything I am working toward.

Instead, I want the repositories to provide reviewable evidence of how I am learning to:

* Understand products, users and important risks
* Design tests around meaningful behaviour
* Investigate failures and verify fixes
* Automate important verification
* Work with persistent data and system state
* Connect automated testing to CI
* Build and test software in small, reviewable steps
* Use AI as an engineering and QA tool while keeping human review and verification explicit
* Document technical decisions, results, limitations and remaining risks

The progression matters as much as the individual technologies.

---

## Background

Before moving into software testing, I worked with sports development, project management, coaching and education.

That experience continues to influence how I approach technical work: understanding the purpose before choosing the solution, identifying risks early, communicating clearly, working systematically with feedback and improving through repeated verification.

I am now combining that experience with software testing, automation, programming and Quality Engineering while studying toward my software testing qualification.

---

## Contact

Email: [johan@bergochhav.nu](mailto:johan@bergochhav.nu)
Location: Stockholm, Sweden
GitHub: https://github.com/Zion8a
