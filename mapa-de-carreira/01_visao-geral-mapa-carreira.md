---
title: "Visão Geral do Mapa de Carreira em Tecnologia"
description: "Introdução, visão geral, diagrama e estrutura dos pilares do mapa de carreira para times de tecnologia."
author: "Equipe de Carreiras Tech"
created_date: "2024-06-10"
updated_date: "2024-06-10"
version: "1.0"
status: "published"
confidence: "high"
tags:
  - mapa-carreira
  - tech-roles
  - visão-geral
categories:
  - Carreira
  - Tecnologia
language: "pt-BR"
---

# 🗺️ Visão Geral do Mapa de Carreira {#visao-geral-mapa-carreira}

<!-- summary:start -->
> Este documento apresenta a visão geral, estrutura e pilares do mapa de carreira para times de tecnologia, incluindo o diagrama de progressão e explicação dos principais caminhos profissionais.
<!-- summary:end -->

## 🏛️ Estrutura Visual do Mapa de Carreira

```mermaid
%%{init: { "themeVariables": { "fontFamily": "Arial", "fontSize": "10px" } }}%%
flowchart TD
    subgraph Engenharia de Software
        ES1[Engenheiro de Software Jr]
        ES2[Engenheiro de Software Pl]
        ES3[Engenheiro de Software Sr]
        ES4[Engenheiro de Software Especialista]
        TL1[Tech Lead]
        AS1[Arquiteto de Solução]
        HE1[Head de Engenharia]
        VP1[VP de Engenharia / CTO]
        ES1 --> ES2 --> ES3 --> ES4 --> TL1 --> AS1 --> HE1 --> VP1
    end

    subgraph Dados e IA
        ED1[Engenheiro de Dados Jr]
        ED2[Engenheiro de Dados Pl]
        ED3[Engenheiro de Dados Sr]
        ESP1[Especialista em IA/ML]
        TLD[Tech Lead de Dados]
        AD[Arquiteto de Dados]
        HD[Head de Dados e IA]
        CDO[Chief Data Officer]
        ED1 --> ED2 --> ED3 --> ESP1 --> TLD --> AD --> HD --> CDO
    end

    subgraph Infraestrutura e DevOps
        EC1[Engenheiro de Cloud Jr]
        EC2[Engenheiro de Cloud Pl]
        SRE[Engenheiro DevOps/SRE Sr]
        ER[Especialista em Reliability]
        TLI[Tech Lead de Infraestrutura]
        AN[Arquiteto de Nuvem]
        HI[Head de Infraestrutura]
        EC1 --> EC2 --> SRE --> ER --> TLI --> AN --> HI
    end

    subgraph Segurança e Compliance
        ACS1[Analista de Cyber Segurança Jr]
        ACS2[Analista de Cyber Segurança Pl]
        ACS3[Analista de Cyber Segurança Sr]
        EC[Especialista em Compliance]
        TLS[Tech Lead de Segurança]
        AS[Arquiteto de Segurança]
        HSC[Head de Segurança & Compliance]
        CISO[Chief Information Security Officer]
        ACS1 --> ACS2 --> ACS3 --> EC --> TLS --> AS --> HSC --> CISO
    end

    subgraph Produto e Design
        UX1[UX/UI Designer Jr]
        UX2[UX/UI Designer Pl]
        UX3[UX/UI Designer Sr]
        PO[Product Owner]
        PDL[Product Designer Lead]
        HPD[Head de Produto & Design]
        VP2[VP de Produto]
        UX1 --> UX2 --> UX3 --> PDL --> HPD --> VP2
        PO --> HPD
    end

    style Engenharia de Software fill:#e3f2fd,stroke:#2196f3,stroke-width:2px
    style Dados e IA fill:#e8f5e9,stroke:#43a047,stroke-width:2px
    style Infraestrutura e DevOps fill:#fffde7,stroke:#fbc02d,stroke-width:2px
    style Segurança e Compliance fill:#ffebee,stroke:#e53935,stroke-width:2px
    style Produto e Design fill:#f3e5f5,stroke:#8e24aa,stroke-width:2px
```

Este mapa de carreira define a progressão profissional para profissionais de tecnologia, contemplando tanto trilhas individuais quanto gerenciais. A estrutura está organizada em cinco pilares principais, permitindo especialização técnica profunda ou transição para funções de liderança.

## 📑 Índice das Seções Relacionadas

- [Pilares Organizacionais](02_pilares-organizacionais.md)
- [Trilhas Profissionais](03_trilhas-profissionais.md)
- [Níveis de Senioridade](04_niveis-senioridade.md)
- [Competências Transversais](05_competencias-transversais.md)
- [Matriz de Carreira](06_matriz-carreira.md)
- [Referências do Mapa de Carreira](07_referencias-mapa-carreira.md)
