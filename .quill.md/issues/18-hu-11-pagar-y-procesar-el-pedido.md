---
id: 18
title: 'HU-11: Pagar y procesar el pedido'
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
    id: 3
  - type: depends_on
    id: 17
---

<!-- [SECTION_START: acceptance] -->

**Dado** que se paga la orden,
**Cuando** el Webhook valida la firma HMAC,
**Entonces** el estado cambia a CONFIRMED.

<!-- [SECTION_END: acceptance] -->

<!-- [SECTION_START: user_story] -->

**Como** Sistema,
**Quiero** pagar y procesar el pedido,
**Para** registrar pagos vía Lemon Squeezy.

<!-- [SECTION_END: user_story] -->
