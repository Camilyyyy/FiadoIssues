---
id: 79
title: 'Módulo Principal: Canal de Ventas Mayorista B2B'
author: AI Agent (MCP)
creation_date: '2026-07-03'
updated_date: '2026-07-03'
issue_type: module
status: in_progress
assignee: pm-1
labels: []
relations:
  - type: child
    id: 73
  - type: child
    id: 74
  - type: child
    id: 75
  - type: child
    id: 76
  - type: child
    id: 77
  - type: child
    id: 78
---

<!-- [SECTION_START: description] -->

Módulo de Alto Nivel que engloba toda la arquitectura del Canal de Ventas Mayorista B2B.

```mermaid
flowchart TD
    %% Nodo Principal
    P[Módulo Principal: Sistema de Gestión B2B]

    %% Módulos Secundarios
    M1(Módulo 1: Canal de WhatsApp)
    M2(Módulo 2: Catálogo y Visualización)
    M3(Módulo 3: Pedidos y Transacciones)
    M4(Módulo 4: Dashboard y Métricas)
    M5(Módulo 5: Usuarios y Seguridad)
    M6(Módulo 6: Gestión de Catálogo y Configuración)
    
    %% Relaciones
    P --> M1
    P --> M2
    P --> M3
    P --> M4
    P --> M5
    P --> M6

    %% Actores
    A([Administrador])
    C([Comprador Mayorista])
    V([Vendedor])

    A --> P
    C --> P
    V --> P
```

<!-- [SECTION_END: description] -->
