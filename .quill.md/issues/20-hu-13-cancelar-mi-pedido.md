---
id: 20
title: 'HU-13: Cancelar mi pedido'
author: AI Agent (MCP)
creation_date: '2026-07-03'
updated_date: '2026-07-03'
issue_type: user-story
status: ready
assignee: dev-1
labels:
  - frontend
story_points: '2'
relations:
  - type: parent
    id: 3
  - type: depends_on
    id: 19
---

<!-- [SECTION_START: acceptance] -->

**Dado** que el estado es PENDING,
**Cuando** presiono cancelar,
**Entonces** el registro muta a CANCELLED y libera stock.

<!-- [SECTION_END: acceptance] -->

<!-- [SECTION_START: user_story] -->

**Como** Comprador,
**Quiero** cancelar mi pedido,
**Para** anular compras no deseadas.

<!-- [SECTION_END: user_story] -->
