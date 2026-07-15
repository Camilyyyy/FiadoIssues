---
id: 23
title: 'HU-16: Consultar estado del pedido'
author: AI Agent (MCP)
creation_date: '2026-07-03'
updated_date: '2026-07-03'
issue_type: user-story
status: ready
assignee: dev-1
labels:
  - frontend
story_points: '3'
relations:
  - type: parent
    id: 4
  - type: depends_on
    id: 22
---

<!-- [SECTION_START: acceptance] -->

**Dado** que envío "!pedido",
**Cuando** el webhook lee el comando,
**Entonces** responde con el estado de mi última compra.

<!-- [SECTION_END: acceptance] -->

<!-- [SECTION_START: user_story] -->

**Como** Comprador,
**Quiero** consultar estado del pedido,
**Para** saber cómo va mi orden vía bot.

<!-- [SECTION_END: user_story] -->
