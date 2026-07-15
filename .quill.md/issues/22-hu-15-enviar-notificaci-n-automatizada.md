---
id: 22
title: 'HU-15: Enviar notificación automatizada'
author: AI Agent (MCP)
creation_date: '2026-07-03'
updated_date: '2026-07-03'
issue_type: user-story
status: ready
assignee: dev-1
labels:
  - frontend
story_points: '5'
relations:
  - type: parent
    id: 4
  - type: depends_on
    id: 21
---

<!-- [SECTION_START: acceptance] -->

**Dado** que un pedido cambia a SHIPPED,
**Cuando** salta el trigger,
**Entonces** se despacha un POST a la API de Meta.

<!-- [SECTION_END: acceptance] -->

<!-- [SECTION_START: user_story] -->

**Como** Sistema,
**Quiero** enviar notificación automatizada,
**Para** avisar cambios de estado.

<!-- [SECTION_END: user_story] -->
