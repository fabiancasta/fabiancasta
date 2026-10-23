# Fabián Andrés Castaño Ramírez

**Engineering Manager · Experto en Odoo · Ingeniero de Agentes de IA**

Medellín, Colombia · Remoto · fabian_casta@hotmail.com · [LinkedIn](https://www.linkedin.com/in/fabian-castano/) · [GitHub](https://github.com/fabiancasta)

## Perfil

Ingeniero de Sistemas con más de 15 años en desarrollo de software y más de 8 especializado en Odoo (v13–v20, Community y Enterprise). Hoy me enfoco en llevar agentes de IA a sistemas de negocio reales —ERP, CRM, sitios web— con la gobernanza que los hace seguros en producción: políticas de mínimo privilegio, detección de comportamiento anómalo, auditoría a prueba de manipulación y salvaguardas que impiden tocar producción por error. Experiencia en desarrollo y migración de módulos, Odoo.sh y servidores Linux, facturación electrónica (DIAN, SII), Docker, ETL y Datawarehouse, y liderazgo técnico de equipos remotos.

## Agentes de IA — proyectos destacados

- **[odoo-mcp-governed](https://github.com/fabiancasta/odoo-mcp-governed)** (código abierto, MIT). Servidor MCP que permite a agentes de IA trabajar dentro de Odoo bajo gobernanza: cada llamada se valida contra una política, se puntúa con 8 detectores de comportamiento y se registra en un log de auditoría encadenado con hashes y sellado con HMAC. Protocolo MCP implementado desde cero (stdio y HTTP), 18 herramientas, perfiles multi-instancia con cambio en caliente, panel de administración sin JavaScript y Docker endurecido. 215 pruebas; las de seguridad clave, verificadas por mutación.
  - Detecté y cerré una evasión real: borrados lanzados *en paralelo* esquivaban el detector de ráfagas. Lo resolví serializando por agente y lo demostré con una prueba que falla si se quita la corrección.
- **Servidor MCP de Odoo endurecido para uso diario**: arranque que falla cerrado sin secretos, validación estricta de JWT, sesiones aleatorias, lista negra de modelos en cada herramienta, límites de tamaño, cabeceras de seguridad y contenedor endurecido. Verificado con 48 pruebas automáticas contra un Odoo real.
- **Agente autónomo de contenidos** que publica un artículo diario vía MCP (WordPress), con verificación automática de SEO y datos estructurados, validación de NIT y un agente de auditoría semanal. En operación diaria desde septiembre de 2026.
- **Pipeline comercial con agentes**: contacto por SMS y WhatsApp (plantillas aprobadas por Meta, Twilio), agente de voz con IA para llamadas entrantes (ElevenLabs) e integración con Odoo CRM.

## Experiencia

### Ingeniero de Sistemas, responsable de TI (contratista) — Alcaldía de Cocorná (Antioquia)
*Agosto 2026 – actualidad*

Responsable de sistemas de la alcaldía: soporte integral a todas las dependencias en redes, software, hardware y seguridad informática.
- Administración de la red: configuración de routers, concentradores y WiFi; diagnóstico y solución de fallas.
- Soporte de software y hardware: mantenimiento y reparación de computadores e impresoras en todas las dependencias.
- Seguridad informática de la infraestructura municipal.
- Capacitación a funcionarios en el uso de los equipos, la red y buenas prácticas.

### Responsable de Desarrollo Odoo v13–v19 (Enterprise y Community) — ERP GT Systems
*Julio 2025 – actualidad · Remoto, Guatemala*

Lidero el desarrollo, la infraestructura con Docker y la integración de IA para soluciones empresariales sobre Odoo Enterprise. Desarrollo tecnología propia basada en MCP para hacer la consultoría Odoo más estratégica, eficiente y escalable.

### Fundador — DonPedroFactura.Com (fábrica de software)
*2016 – actualidad · Colombia*

Soluciones Odoo para pymes latinoamericanas (hoy sobre la versión 19): punto de venta, facturación electrónica DIAN y ERP agroalimentario. Módulos publicados en la Odoo App Store. Laboratorio de agentes de IA de los proyectos anteriores.

### Desarrollador Odoo Senior — Bits Americas
*Febrero 2024 – junio 2025 · Remoto, Colombia*
- Desarrollé y migré módulos personalizados de Odoo de la versión 13 a la 18.
- Administré instancias Odoo.sh y servidores VPS Linux, garantizando disponibilidad y rendimiento.
- Integré APIs de facturación electrónica con sistemas de terceros para clientes de varios países.
- Coordiné despliegues y versionamiento en entornos Docker con control de calidad.
- Mentoricé a desarrolladores junior, mejorando los tiempos de entrega; resolví tickets dentro del SLA.

### Líder de Desarrollo — Consulnet
*Septiembre 2022 – febrero 2024 · Remoto, Chile*
- Desarrollé y mantuve módulos Odoo en versiones 13 a 17 (Community y Enterprise).
- Lideré la migración completa del módulo de facturación electrónica de Odoo v13 a v17.
- Diseñé políticas de backup y protocolos de seguridad para servidores de producción.
- Gestioné la plataforma Docker, reduciendo de forma significativa los fallos críticos en producción.

### Ingeniero de Sistemas — Brain & Help Ltda
*Enero 2010 – mayo 2021 · Medellín, Colombia*
- Diseñé e implementé un ERP completo en Python y PostgreSQL para clientes internos.
- Implementé soluciones ETL y administré plataformas de Datawarehouse.
- Configuré y administré servidores VPS Linux, reduciendo incidentes operativos.
- Desarrollé y migré módulos Odoo para distintas versiones.

### Ingeniero de Sistemas (temporal) — FALCON S.A.
*Julio 2009 – septiembre 2009 · Barranquilla*

Código SQL y procesos ETL en PostgreSQL y Oracle 10.

### Ingeniero de Sistemas — Electricaribe
*Julio 2007 – abril 2008 · Barranquilla*
- Programas ETL para el Datawarehouse de facturación y consumo energético.
- Algoritmos PL/SQL para procesamiento masivo de datos.
- Ingeniería inversa de sistemas legacy de facturación para su modernización.

## Educación

- **Ingeniero de Sistemas** — Universidad Autónoma del Caribe, 2006
- **MBA + Máster en Big Data y Business Intelligence** — ENEB, Escuela de Negocios Europea de Barcelona (en curso)

## Certificaciones y cursos

Matsuo-Iwasawa Lab, Universidad de Tokio · Ciencia de Datos (CGI) · Odoo Funcional e Implementadores v13–v18 · GitHub Copilot y OpenAI aplicados al desarrollo · Principios SOLID y Clean Code · Lógica de programación y pruebas técnicas · Python asistido con IA · Gestión de equipos y trabajo remoto · Comunicación avanzada

## Habilidades técnicas

- **Agentes e IA:** Model Context Protocol (servidores, transportes, diseño de herramientas), Claude API, Claude Code, LangChain / LangGraph, gobernanza de agentes, GitHub Copilot
- **ERP / Odoo:** v13–v19, Community y Enterprise — desarrollo, migración, administración, implementación funcional, Odoo.sh
- **Lenguajes y datos:** Python, SQL, PL/SQL, XML · PostgreSQL, Oracle · ETL, Datawarehouse
- **DevOps y seguridad:** Docker, VPS Linux, endurecimiento de contenedores, JWT, CSRF/CSP, Git, GitHub, Bitbucket
- **Integraciones:** REST, SOAP, JSON-RPC, facturación electrónica (DIAN, SII), Twilio, ElevenLabs, WordPress, Google Analytics 4
- **Metodologías:** Scrum, liderazgo técnico, mentoría, trabajo remoto

## Idiomas

Español: nativo · Inglés: lectura técnica (documentación, APIs, frameworks)
