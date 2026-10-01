# Diêgo Azevedo

Solutions architect. Boa Vista, Brazil — remote. Fifteen years in software:
programming, project management, systems analysis and architecture. Recent
work focused on agentic systems.

## Control layer

Agentic systems deliver the artifact and, with it, the claim that the artifact
is correct. The two are not the same thing.

The work consists of building what makes that gap visible before production:

- **Specification before implementation.** The system operates against a
  written specification, not against a conversation.
- **Acceptance criteria as a gate.** A phase closes when the criteria pass, not
  when the system declares it complete.
- **Adversarial audit of the raw artifact.** A separate session re-runs the
  proofs against the code itself. The one who implements does not audit.

None of this is new. It is software engineering discipline — the same
discipline that, in another context, became standard operating procedure
subject to regulatory authority. Part of these ideas was rediscovered under
other names in AI-assisted development, not always with what made them useful:
separation of roles, reproducible proof, and a gate that does not depend on
opinion.

## Featured

**[metodo-auditado](https://github.com/diegoazevedo-inov/metodo-auditado)** —
the method, written down. Separated roles, measurement before opinion, and a
checker that is only put to use after it catches a planted defect. First full
application: the UI debt of a production web app brought to zero, with
permanent checks in place. Documentation in Portuguese, summary in English.

## Recent work

- Hardened MCP server: schema-validated tools, human approval in the loop,
  self-approval blocked at the database level.
- Multi-tenant platform on PostgreSQL row-level security, with an automated
  test suite.

TypeScript · NestJS · Next.js · PostgreSQL · Prisma · Redis · BullMQ ·
Playwright · Docker · Python

## Domain and security

Medical imaging, DICOM and clinical workflows hold the greatest domain depth —
not the limit of the scope. Open tools from that front:
[LogosBalancaDicom](https://github.com/diegoazevedo-inov/LogosBalancaDicom) and
[LogosDICOMFilm](https://github.com/diegoazevedo-inov/LogosDICOMFilm), each a
single HTML file that runs in the browser.

Information security since 2022. ISO/IEC 27001 as the compliance reference;
LGPD in current practice.

## Languages

Portuguese, native. Spanish and Italian, advanced. English: solid reading and
listening; conversation in development.
