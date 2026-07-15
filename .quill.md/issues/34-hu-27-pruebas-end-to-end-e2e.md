---
id: 34
title: 'HU-27: Pruebas End-to-End (E2E)'
author: AI Agent (MCP)
creation_date: '2026-07-03'
updated_date: '2026-07-03'
issue_type: user-story
status: ready
assignee: dev-1
labels:
  - frontend
story_points: '8'
relations:
  - type: parent
    id: 7
  - type: depends_on
    id: 33
---

<!-- [SECTION_START: acceptance] -->

**Dado** que el sistema está en el entorno de Staging,
**Cuando** ejecuto los flujos de agregar al carrito y checkout,
**Entonces** la transacción finaliza sin bloqueos en la interfaz.

<!-- [SECTION_END: acceptance] -->

<!-- [SECTION_START: user_story] -->

**Como** Analista de QA,
**Quiero** ejecutar pruebas End-to-End (E2E) simulando los flujos del comprador y administrador,
**Para** validar la integración completa de los componentes en la UI.

<!-- [SECTION_END: user_story] -->
