# Diêgo Azevedo

Solutions architect based in Boa Vista, Brazil. Fifteen years in software: programmer, project manager, systems analyst and architect. Most of my recent work is AI systems.

## What I do

I design the control layer around coding agents.

An agent hands you code and a summary that says the work is done. A convincing summary does not guarantee correct code. I have found a security defect in a component that the agent's own summary had declared compliant.

So I don't trust the summary. I build the process around it:

- **Specification before implementation.** The agent works against a written spec, not a conversation.
- **Acceptance criteria as a gate.** A phase is done when its criteria pass, not when the agent says so.
- **Adversarial audit of the raw artifact.** A separate session re-runs the proofs against the code itself. The one who implements never audits.

## Featured

**[metodo-auditado](https://github.com/diegoazevedo-inov/metodo-auditado)** is that method, written down: separated roles, measurement before opinion, and checkers that must catch a planted defect before anyone relies on them. Its first full application took a production web app's UI debt to zero and left checks in place to keep it there. Docs are in Portuguese, with an English summary.

## Recent work

- A hardened MCP server: schema-validated tools, human approval in the loop, and self-approval blocked at the database level.
- A multi-tenant platform built on PostgreSQL row-level security, with an automated test suite.

Stack: TypeScript, NestJS, Next.js, PostgreSQL, Prisma, Redis, BullMQ, Playwright, Docker, Python.

## Domain and security

Healthcare is where my domain knowledge runs deepest: medical imaging, DICOM, clinical workflows. It is not the limit of what I build. Two small open tools from that side: [LogosBalancaDicom](https://github.com/diegoazevedo-inov/LogosBalancaDicom) and [LogosDICOMFilm](https://github.com/diegoazevedo-inov/LogosDICOMFilm), both single HTML files that run in the browser.

Information security since 2022, with ISO/IEC 27001 as my reference framework and LGPD, Brazil's data protection law, in day-to-day practice.

## Languages

Portuguese, native. Spanish and Italian, advanced. English: strong reading and listening; speaking in progress.
