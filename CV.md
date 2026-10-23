# Fabián Andrés Castaño Ramírez

**Engineering Manager · Odoo Expert · Agentic Engineer**

Medellín, Colombia · Remote · fabian_casta@hotmail.com · [LinkedIn](https://www.linkedin.com/in/fabian-castano/) · [GitHub](https://github.com/fabiancasta)

## Summary

Systems engineer with 15+ years in software development and 8+ years specialised in Odoo (v13–v20, Community and Enterprise). I now focus on bringing AI agents into real business systems — ERPs, CRMs, websites — with the governance that makes them safe in production: least-privilege policy, behavioural anomaly detection, tamper-evident auditing and safeguards that make touching production by mistake impossible. Background in module development and migration, Odoo.sh and Linux servers, e-invoicing (DIAN, SII), Docker, ETL and data warehousing, and technical leadership of remote teams.

## AI agents — selected work

- **[odoo-mcp-governed](https://github.com/fabiancasta/odoo-mcp-governed)** (open source, MIT). An MCP server that lets AI agents work inside Odoo under governance: every tool call is policy-checked, risk-scored by 8 behavioural detectors and recorded in a hash-chained, HMAC-sealed audit log. MCP protocol implemented from scratch (stdio and HTTP), 18 tools, multi-instance profiles with hot swap, a script-free admin panel and hardened Docker. 215 tests; key security tests mutation-checked.
  - Found and closed a real bypass: deletes fired *in parallel* evaded burst detection. Fixed with per-agent serialisation, proven by a test that fails when the fix is removed.
- **Hardened Odoo MCP server in daily use:** fail-closed startup without secrets, strict JWT validation, random admin sessions, a model denylist enforced in every tool, request size limits, security headers, container hardening. Verified with 48 automated tests against a live Odoo.
- **Autonomous content agent** publishing a daily article through MCP (WordPress), with automated SEO and structured-data checks, tax-ID validation and a separate weekly audit agent. Running daily since September 2026.
- **Agentic sales pipeline:** SMS and WhatsApp outreach (Meta-approved templates via Twilio), an AI voice agent for inbound calls (ElevenLabs), Odoo CRM integration.

## Experience

### Systems Engineer, IT lead (contractor) — Municipality of Cocorná (Antioquia, Colombia)
*August 2026 – present*

The municipality's systems lead: end-to-end support for every department across networks, software, hardware and IT security.
- Network administration: router, hub and Wi-Fi configuration; network troubleshooting.
- Software and hardware support: maintenance and repair of computers and printers across all departments.
- IT security for the municipal infrastructure.
- Staff training on equipment, network use and good practices.

### Head of Odoo Development, v13–v19 (Enterprise & Community) — ERP GT Systems
*July 2025 – present · Remote, Guatemala*

Lead development, Docker infrastructure and AI integration for enterprise solutions on Odoo Enterprise. Building in-house MCP-based technology to make Odoo consulting more strategic, efficient and scalable.

### Founder — DonPedroFactura.Com (software factory)
*2016 – present · Colombia*

Odoo solutions for Latin American SMEs (currently on version 19): point of sale, DIAN e-invoicing, agri-food ERP. Modules published on the Odoo App Store. The proving ground for the agent work above.

### Senior Odoo Developer — Bits Americas
*February 2024 – June 2025 · Remote, Colombia*
- Developed and migrated custom Odoo modules from v13 to v18.
- Administered Odoo.sh instances and Linux VPS servers for availability and performance.
- Integrated e-invoicing APIs with third-party systems for clients in several countries.
- Coordinated Docker-based deployments and versioning with quality control.
- Mentored junior developers, improving delivery times; resolved tickets within SLA.

### Development Lead — Consulnet
*September 2022 – February 2024 · Remote, Chile*
- Developed and maintained custom Odoo modules, v13–v17 (Community and Enterprise).
- Led the full migration of the e-invoicing module from Odoo v13 to v17.
- Designed backup policies and security protocols for production servers.
- Managed the Docker platform, significantly reducing critical production failures.

### Systems Engineer — Brain & Help Ltda
*January 2010 – May 2021 · Medellín, Colombia*
- Designed and built a complete ERP in Python and PostgreSQL for internal clients.
- Implemented ETL solutions and administered data warehouse platforms.
- Set up and administered Linux VPS servers, reducing operational incidents.
- Developed and migrated Odoo modules across versions.

### Systems Engineer (temporary) — FALCON S.A.
*July 2009 – September 2009 · Barranquilla*

SQL and ETL processes on PostgreSQL and Oracle 10.

### Systems Engineer — Electricaribe
*July 2007 – April 2008 · Barranquilla*
- ETL programs for the billing and energy-consumption data warehouse.
- PL/SQL algorithms for high-volume data processing.
- Reverse engineering of legacy billing systems for platform modernisation.

## Education

- **Systems Engineering (BSc)** — Universidad Autónoma del Caribe, 2006
- **MBA + MSc in Big Data and Business Intelligence** — ENEB, European Business School of Barcelona (in progress)

## Certifications and courses

Matsuo-Iwasawa Lab, University of Tokyo · Data Science (CGI) · Odoo Functional & Implementer v13–v18 · GitHub Copilot and OpenAI for software development · SOLID principles and Clean Code · Programming logic and technical tests · AI-assisted Python · Team management and remote work · Advanced communication

## Technical skills

- **Agents & AI:** Model Context Protocol (servers, transports, tool design), Claude API, Claude Code, LangChain / LangGraph, agent governance, GitHub Copilot
- **ERP / Odoo:** v13–v19, Community and Enterprise — development, migration, administration, functional implementation, Odoo.sh
- **Languages & data:** Python, SQL, PL/SQL, XML · PostgreSQL, Oracle · ETL, data warehousing
- **DevOps & security:** Docker, Linux VPS, container hardening, JWT, CSRF/CSP, Git, GitHub, Bitbucket
- **Integrations:** REST, SOAP, JSON-RPC, e-invoicing (DIAN, SII), Twilio, ElevenLabs, WordPress, Google Analytics 4
- **Methods:** Scrum, technical leadership, mentoring, remote work

## Languages

Spanish: native · English: technical reading (documentation, APIs, frameworks)
