# Diêgo Azevedo

**Português** · [English](#english) · [Español](#español)

Arquiteto de soluções e especialista em saúde digital e IA. Ponta a ponta: do
requisito à arquitetura, ao código, à infraestrutura, à segurança e à operação.
Boa Vista, Brasil — presencial, híbrido ou remoto, inclusive com mudança.

Quinze anos construindo e operando software em produção, doze deles também na
gestão de projetos e equipes, em redes públicas de saúde e ambientes regulados.
Inteligência artificial desde 2019; sistemas agênticos em produção desde 2025.

## Foco

Sistemas agênticos entregam o artefato e, junto, a afirmação de que ele está
correto. As duas coisas não são a mesma. O trabalho é a camada de controle que
as separa, e a evidência que decide entre opções:

- **Especificação antes da implementação** (spec-driven development).
- **Critério de aceite como portão.**
- **Auditoria adversarial do artefato bruto.** Quem implementa não audita.
- **Medição antes de opinião.** Tecnologia e processo se escolhem contra
  requisitos, com a regra de decisão fixada antes dos dados.

## Trabalho publicado

Método e ferramentas, em código aberto:

- **[metodo-auditado](https://github.com/diegoazevedo-inov/metodo-auditado)** —
  método para construir software com sistemas agênticos: papéis separados,
  medição antes de opinião, verificadores provados por defeitos plantados.
  Primeira aplicação: uma aplicação web em produção saiu de 60 rotas com
  transbordo de layout e 6.606 cores fixas no código para zero.
  DOI [10.5281/zenodo.24237079](https://doi.org/10.5281/zenodo.24237079).
- **[decisao-medida](https://github.com/diegoazevedo-inov/decisao-medida)** —
  protocolo para decidir tecnologia e processo com evidência: requisitos e
  regra de decisão fixados antes da coleta, opções medidas na mesma bancada e
  previsão conferida em data marcada.
  DOI [10.5281/zenodo.24139207](https://doi.org/10.5281/zenodo.24139207).
- **[espelho-backlog](https://github.com/diegoazevedo-inov/espelho-backlog)** —
  fonte única de backlog espelhada para Jira, Trello e GitHub Projects, com
  idempotência e fidelidade verificável. Cinquenta testes, cinquenta defeitos
  plantados. DOI [10.5281/zenodo.24237082](https://doi.org/10.5281/zenodo.24237082).

Dados reproduzíveis e perícia:

- **[caged-municipio](https://github.com/diegoazevedo-inov/caged-municipio)** —
  Novo CAGED por município e ocupação, conferido contra a divulgação oficial e
  com auditoria independente.
  DOI [10.5281/zenodo.24199769](https://doi.org/10.5281/zenodo.24199769).
- **[rastreio-onchain](https://github.com/diegoazevedo-inov/rastreio-onchain)** —
  método somente-leitura para rastrear USDT (TRC-20) após fraude e conferir
  promessas de "recuperação" contra a blockchain, com caso encenado em rede de
  teste.
  DOI [10.5281/zenodo.24296844](https://doi.org/10.5281/zenodo.24296844).

Imagem em saúde:

- **[LogosDICOMFilm](https://github.com/diegoazevedo-inov/LogosDICOMFilm)** e
  **[LogosBalancaDicom](https://github.com/diegoazevedo-inov/LogosBalancaDicom)** —
  ferramentas DICOM, cada uma num único arquivo HTML que roda no navegador.

## Áreas

- **Saúde digital:** HIS, RIS, PACS e DICOM em redes públicas e privadas de três
  estados; estações de laudo, impressão e gravação de exames.
- **Sistemas agênticos:** servidores MCP com aprovação humana, A2A entre agentes
  especializados, roteamento de modelos por perfil e tarefa com custo medido
  por resposta, canários de comportamento.
- **Recuperação e dados:** RAG com pgvector, busca híbrida, re-ranking e
  GraphRAG; embeddings locais; Spark e MLOps desde 2019.
- **Visão computacional, voz e automação:** visão com câmeras e drones desde
  2019; transcrição e síntese de voz; automação de processos.
- **Infraestrutura e redes:** Linux, containers, virtualização, proxies com TLS,
  roteadores e switches gerenciados, monitoramento de servidores.
- **IoT e equipamentos:** leitura de equipamentos por Modbus TCP, telemetria por
  MQTT, diagnóstico veicular OBD-II e automação residencial por APIs locais.
- **Segurança da informação:** proteção de produtos e infraestrutura,
  avaliações de postura, resposta a incidente, ISO/IEC 27001, LGPD.
- **Gestão de projetos e produto:** Scrum, Kanban, backlog, requisitos e
  critérios de aceite; equipes de até oito pessoas.
- **Educação pública:** orientação técnica de um projeto de feira de ciências do
  ensino médio público — app offline de educação financeira e um agente em que
  o modelo interpreta e fórmulas testadas calculam.

## Stack

- **Linguagens:** TypeScript · JavaScript · Java · Python · SQL · Bash
- **Back end e front end:** Node.js · NestJS · Next.js · React · Tailwind ·
  Django · J2EE (JSF, RichFaces, Maven)
- **Dados:** PostgreSQL · pgvector · MySQL · SQLite (FTS5) · Redis · BullMQ ·
  Prisma · Spark
- **IA:** MCP (SDK TypeScript e Python) · A2A · LangGraph e Pydantic AI (bancada
  comparativa) · RAG · ONNX Runtime e transformers.js · APIs Anthropic, Gemini e
  OpenAI · Vertex AI · Speech-to-Text e Text-to-Speech (Chirp 3) · visão
  computacional · desenvolvimento assistido por IA (Claude Code e outros)
- **Saúde:** DICOM (pydicom, pynetdicom, GDCM, dcm4chee, OHIF, Weasis) · HL7 ·
  HIS · RIS · PACS
- **Infraestrutura:** Linux · Docker e Compose · KVM · systemd · Caddy · nginx ·
  certbot · Google Cloud (Cloud Run, Vertex AI) · GitHub Actions · Keycloak e
  OpenLDAP
- **Redes e equipamentos:** RouterOS API · SNMP · Redfish (iDRAC) · UniFi ·
  MQTT (Mosquitto) · Modbus TCP · OBD-II
- **Qualidade:** Playwright · Jest · pytest · testes com defeito plantado · CI
- **Legado Windows:** HTA · JScript · IMAPI2

## Formação

Tecnólogo em Análise e Desenvolvimento de Sistemas — Instituto Federal de
Roraima.
Especialização em Saúde Digital — Universidade Federal de Goiás.

## Idiomas

Português, nativo. Espanhol, avançado. Inglês: leitura e compreensão sólidas;
conversação em desenvolvimento.

---

<details>
<summary><b id="english">English</b></summary>

Solutions architect and digital health & AI specialist. Full cycle: from
requirements to architecture, code, infrastructure, security and operations.
Boa Vista, Brazil — on-site, hybrid or remote, including relocation.

Fifteen years building and running software in production, twelve of them also
managing projects and teams, in public health networks and regulated
environments. Artificial intelligence since 2019; agentic systems in production
since 2025.

### Focus

Agentic systems deliver the artifact and, with it, the claim that the artifact
is correct. The two are not the same thing. The work is the control layer that
keeps them apart, and the evidence that decides between options:

- **Specification before implementation** (spec-driven development).
- **Acceptance criteria as a gate.**
- **Adversarial audit of the raw artifact.** The one who implements does not audit.
- **Measurement before opinion.** Technology and process are chosen against
  requirements, with the decision rule fixed before the data.

### Published work

Method and tools, open source:

- **[metodo-auditado](https://github.com/diegoazevedo-inov/metodo-auditado)** —
  a method for building software with agentic systems: separated roles,
  measurement before opinion, checkers proven by planted defects. First
  application: a production web app from 60 routes with layout overflow and
  6,606 hard-coded colors to zero.
  DOI [10.5281/zenodo.24237079](https://doi.org/10.5281/zenodo.24237079).
- **[decisao-medida](https://github.com/diegoazevedo-inov/decisao-medida)** —
  a protocol for choosing technology and process with evidence: requirements
  and decision rule fixed before collection, options measured on the same
  bench, a prediction checked on a set date.
  DOI [10.5281/zenodo.24139207](https://doi.org/10.5281/zenodo.24139207).
- **[espelho-backlog](https://github.com/diegoazevedo-inov/espelho-backlog)** —
  one backlog source of truth mirrored into Jira, Trello and GitHub Projects,
  with idempotence and verifiable fidelity. Fifty tests, fifty planted defects.
  DOI [10.5281/zenodo.24237082](https://doi.org/10.5281/zenodo.24237082).

Reproducible data and forensics:

- **[caged-municipio](https://github.com/diegoazevedo-inov/caged-municipio)** —
  Brazil's formal-employment records (Novo CAGED) by municipality and
  occupation, checked against the official release and independently audited.
  DOI [10.5281/zenodo.24199769](https://doi.org/10.5281/zenodo.24199769).
- **[rastreio-onchain](https://github.com/diegoazevedo-inov/rastreio-onchain)** —
  a read-only method to trace USDT (TRC-20) after fraud and check "recovery"
  claims against the blockchain, with a staged case on a test network.
  DOI [10.5281/zenodo.24296844](https://doi.org/10.5281/zenodo.24296844).

Health imaging:

- **[LogosDICOMFilm](https://github.com/diegoazevedo-inov/LogosDICOMFilm)** and
  **[LogosBalancaDicom](https://github.com/diegoazevedo-inov/LogosBalancaDicom)** —
  DICOM tools, each a single HTML file that runs in the browser.

### Areas

- **Digital health:** HIS, RIS, PACS and DICOM in public and private networks
  across three states; reporting workstations, film printing and exam CD
  burning.
- **Agentic systems:** MCP servers with human approval, A2A between specialized
  agents, model routing by profile and task with cost measured per answer,
  behavior canaries.
- **Retrieval and data:** RAG with pgvector, hybrid search, re-ranking and
  GraphRAG; local embeddings; Spark and MLOps since 2019.
- **Computer vision, speech and automation:** vision with cameras and drones
  since 2019; speech-to-text and text-to-speech; process automation.
- **Infrastructure and networks:** Linux, containers, virtualization, TLS
  proxies, managed routers and switches, server monitoring.
- **IoT and equipment:** equipment readings over Modbus TCP, telemetry over
  MQTT, OBD-II vehicle diagnostics and home automation through local APIs.
- **Information security:** protection of products and infrastructure, posture
  assessments, incident response, ISO/IEC 27001, LGPD.
- **Project and product management:** Scrum, Kanban, backlog, requirements and
  acceptance criteria; teams of up to eight.
- **Public education:** technical guidance for a public high-school science
  project — an offline financial-education app and an agent where the model
  interprets and tested formulas compute.

### Stack

- **Languages:** TypeScript · JavaScript · Java · Python · SQL · Bash
- **Back end and front end:** Node.js · NestJS · Next.js · React · Tailwind ·
  Django · J2EE (JSF, RichFaces, Maven)
- **Data:** PostgreSQL · pgvector · MySQL · SQLite (FTS5) · Redis · BullMQ ·
  Prisma · Spark
- **AI:** MCP (TypeScript and Python SDKs) · A2A · LangGraph and Pydantic AI
  (comparative bench) · RAG · ONNX Runtime and transformers.js · Anthropic,
  Gemini and OpenAI APIs · Vertex AI · Speech-to-Text and Text-to-Speech
  (Chirp 3) · computer vision · AI-assisted development (Claude Code and others)
- **Health:** DICOM (pydicom, pynetdicom, GDCM, dcm4chee, OHIF, Weasis) · HL7 ·
  HIS · RIS · PACS
- **Infrastructure:** Linux · Docker and Compose · KVM · systemd · Caddy ·
  nginx · certbot · Google Cloud (Cloud Run, Vertex AI) · GitHub Actions ·
  Keycloak and OpenLDAP
- **Networks and equipment:** RouterOS API · SNMP · Redfish (iDRAC) · UniFi ·
  MQTT (Mosquitto) · Modbus TCP · OBD-II
- **Quality:** Playwright · Jest · pytest · planted-defect testing · CI
- **Windows legacy:** HTA · JScript · IMAPI2

### Education

Technologist in Systems Analysis and Development — Federal Institute of Roraima.
Specialization in Digital Health — Federal University of Goiás.

### Languages

Portuguese, native. Spanish, advanced. English: solid reading and listening;
conversation in development.

</details>

<details>
<summary><b id="español">Español</b></summary>

Arquitecto de soluciones y especialista en salud digital e IA. De punta a punta:
del requisito a la arquitectura, el código, la infraestructura, la seguridad y
la operación. Boa Vista, Brasil — presencial, híbrido o remoto, incluso con
mudanza.

Quince años construyendo y operando software en producción, doce de ellos
también en la gestión de proyectos y equipos, en redes públicas de salud y
entornos regulados. Inteligencia artificial desde 2019; sistemas agénticos en
producción desde 2025.

### Enfoque

Los sistemas agénticos entregan el artefacto y, con él, la afirmación de que el
artefacto es correcto. No son lo mismo. El trabajo es la capa de control que los
separa, y la evidencia que decide entre opciones:

- **Especificación antes de la implementación** (spec-driven development).
- **Criterio de aceptación como compuerta.**
- **Auditoría adversarial del artefacto en bruto.** Quien implementa no audita.
- **Medición antes que opinión.** Tecnología y proceso se eligen contra
  requisitos, con la regla de decisión fijada antes de los datos.

### Trabajo publicado

Método y herramientas, de código abierto:

- **[metodo-auditado](https://github.com/diegoazevedo-inov/metodo-auditado)** —
  método para construir software con sistemas agénticos: roles separados,
  medición antes que opinión, verificadores probados con defectos plantados.
  Primera aplicación: una aplicación web en producción pasó de 60 rutas con
  desbordamiento de diseño y 6.606 colores fijos en el código a cero.
  DOI [10.5281/zenodo.24237079](https://doi.org/10.5281/zenodo.24237079).
- **[decisao-medida](https://github.com/diegoazevedo-inov/decisao-medida)** —
  protocolo para decidir tecnología y proceso con evidencia: requisitos y regla
  de decisión fijados antes de la recolección, opciones medidas en el mismo
  banco y una predicción verificada en fecha fija.
  DOI [10.5281/zenodo.24139207](https://doi.org/10.5281/zenodo.24139207).
- **[espelho-backlog](https://github.com/diegoazevedo-inov/espelho-backlog)** —
  fuente única de backlog reflejada en Jira, Trello y GitHub Projects, con
  idempotencia y fidelidad verificable. Cincuenta pruebas, cincuenta defectos
  plantados. DOI [10.5281/zenodo.24237082](https://doi.org/10.5281/zenodo.24237082).

Datos reproducibles y peritaje:

- **[caged-municipio](https://github.com/diegoazevedo-inov/caged-municipio)** —
  registros de empleo formal de Brasil (Novo CAGED) por municipio y ocupación,
  verificados contra la divulgación oficial y con auditoría independiente.
  DOI [10.5281/zenodo.24199769](https://doi.org/10.5281/zenodo.24199769).
- **[rastreio-onchain](https://github.com/diegoazevedo-inov/rastreio-onchain)** —
  método de solo lectura para rastrear USDT (TRC-20) tras un fraude y contrastar
  promesas de "recuperación" con la blockchain, con un caso simulado en red de
  prueba.
  DOI [10.5281/zenodo.24296844](https://doi.org/10.5281/zenodo.24296844).

Imagen en salud:

- **[LogosDICOMFilm](https://github.com/diegoazevedo-inov/LogosDICOMFilm)** y
  **[LogosBalancaDicom](https://github.com/diegoazevedo-inov/LogosBalancaDicom)** —
  herramientas DICOM, cada una en un único archivo HTML que corre en el
  navegador.

### Áreas

- **Salud digital:** HIS, RIS, PACS y DICOM en redes públicas y privadas de tres
  estados; estaciones de informe, impresión y grabación de estudios.
- **Sistemas agénticos:** servidores MCP con aprobación humana, A2A entre agentes
  especializados, enrutamiento de modelos por perfil y tarea con costo medido
  por respuesta, canarios de comportamiento.
- **Recuperación y datos:** RAG con pgvector, búsqueda híbrida, re-ranking y
  GraphRAG; embeddings locales; Spark y MLOps desde 2019.
- **Visión por computadora, voz y automatización:** visión con cámaras y drones
  desde 2019; transcripción y síntesis de voz; automatización de procesos.
- **Infraestructura y redes:** Linux, contenedores, virtualización, proxies con
  TLS, routers y switches gestionados, monitoreo de servidores.
- **IoT y equipos:** lectura de equipos por Modbus TCP, telemetría por MQTT,
  diagnóstico vehicular OBD-II y domótica por APIs locales.
- **Seguridad de la información:** protección de productos e infraestructura,
  evaluaciones de postura, respuesta a incidentes, ISO/IEC 27001, LGPD.
- **Gestión de proyectos y producto:** Scrum, Kanban, backlog, requisitos y
  criterios de aceptación; equipos de hasta ocho personas.
- **Educación pública:** orientación técnica de un proyecto de feria de ciencias
  de la secundaria pública — app sin conexión de educación financiera y un
  agente en el que el modelo interpreta y fórmulas probadas calculan.

### Stack

- **Lenguajes:** TypeScript · JavaScript · Java · Python · SQL · Bash
- **Back end y front end:** Node.js · NestJS · Next.js · React · Tailwind ·
  Django · J2EE (JSF, RichFaces, Maven)
- **Datos:** PostgreSQL · pgvector · MySQL · SQLite (FTS5) · Redis · BullMQ ·
  Prisma · Spark
- **IA:** MCP (SDK TypeScript y Python) · A2A · LangGraph y Pydantic AI (banco
  comparativo) · RAG · ONNX Runtime y transformers.js · APIs de Anthropic,
  Gemini y OpenAI · Vertex AI · Speech-to-Text y Text-to-Speech (Chirp 3) ·
  visión por computadora · desarrollo asistido por IA (Claude Code y otros)
- **Salud:** DICOM (pydicom, pynetdicom, GDCM, dcm4chee, OHIF, Weasis) · HL7 ·
  HIS · RIS · PACS
- **Infraestructura:** Linux · Docker y Compose · KVM · systemd · Caddy · nginx ·
  certbot · Google Cloud (Cloud Run, Vertex AI) · GitHub Actions · Keycloak y
  OpenLDAP
- **Redes y equipos:** RouterOS API · SNMP · Redfish (iDRAC) · UniFi ·
  MQTT (Mosquitto) · Modbus TCP · OBD-II
- **Calidad:** Playwright · Jest · pytest · pruebas con defecto plantado · CI
- **Legado Windows:** HTA · JScript · IMAPI2

### Formación

Tecnólogo en Análisis y Desarrollo de Sistemas — Instituto Federal de Roraima.
Especialización en Salud Digital — Universidad Federal de Goiás.

### Idiomas

Portugués, nativo. Español, avanzado. Inglés: lectura y comprensión sólidas;
conversación en desarrollo.

</details>
