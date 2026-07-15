---
id: 35
title: 'HU-28: Escaneos de seguridad SAST y DAST'
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
    id: 7
  - type: depends_on
    id: 34
---

<!-- [SECTION_START: acceptance] -->

**Dado** que se realiza un Merge Request en GitLab,
**Cuando** corre el pipeline de seguridad estático,
**Entonces** se reportan 0 vulnerabilidades conocidas de severidad Alta o Crítica.

<!-- [SECTION_END: acceptance] -->

<!-- [SECTION_START: user_story] -->

**Como** DevSecOps,
**Quiero** someter el código a escaneos de seguridad estáticos (SAST) y dinámicos (DAST),
**Para** identificar y mitigar vulnerabilidades antes del paso a producción.

<!-- [SECTION_END: user_story] -->
