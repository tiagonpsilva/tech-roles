<!--
title: "Tech Roles - Estrutura para Times de Tecnologia"
description: "Repositório de descrições de cargos e mapa de carreira para times de tecnologia, otimizado para IA, RAG e buscas semânticas."
author: "Tiago N Pinto Silva"
created_date: "2024-06-10"
updated_date: "2024-06-10"
version: "1.0.0"
confidence: "high"
tags:
  - job-descriptions
  - mapa-de-carreira
  - tecnologia
  - cargos
categories:
  - Carreira
  - Tecnologia
language: "pt-BR"
related_docs:
  - id: "senioridade.md"
    title: "Níveis de Senioridade em Tecnologia"
    relationship: "references"
  - id: "job-descriptions/arquiteto-de-solucao.md"
    title: "Arquiteto de Solução"
    relationship: "extends"
  - id: "mapa-de-carreira/mapa-carreira-tech.md"
    title: "Mapa de Carreira Tech"
    relationship: "references"
knowledge_graph:
  concepts:
    - id: "CONCEPT001"
      name: "Job Description"
    - id: "CONCEPT002"
      name: "Mapa de Carreira"
  relationships:
    - from: "CONCEPT001"
      to: "CONCEPT002"
      type: "references"
-->
<!--
⚠️ Bloco acima: metadados para busca semântica e IA. Pode ser ignorado na leitura.
-->
 
<!-- SEMANTIC_ID: DOC-TECH-ROLES-001 -->
<!-- KNOWLEDGE_DOMAIN: Carreira/Tecnologia/JobDescriptions -->
<!-- SEMANTIC_CONFIDENCE: HIGH -->

# 📚 Tech Roles - Estrutura para Times de Tecnologia

<!-- summary:start -->
> Este repositório reúne descrições padronizadas de cargos (Job Descriptions) e o mapa de carreira para times de tecnologia, com foco em clareza, padronização e otimização para fluxos de IA, RAG e buscas semânticas.
<!-- summary:end -->

## 🗂️ Estrutura do Repositório {#estrutura-repositorio}

### 1. 📝 Descrições de Cargos {#descricao-cargos}
A pasta `job-descriptions` contém arquivos markdown detalhados para cada cargo, com a seguinte estrutura:
- Visão geral do cargo
- Conhecimentos essenciais (mandatórios)
- Conhecimentos adicionais (desejáveis)
- Frameworks e guidances de mercado relevantes
- Principais responsabilidades
- Perguntas do dia-a-dia que o profissional precisa responder
- Atuação nos níveis estratégico, tático e operacional
- Competências comportamentais esperadas
- Métricas de sucesso para avaliação de desempenho

#### 📑 Índice de Job Descriptions {#indice-jds}

Abaixo estão os links diretos para as descrições de cargos disponíveis na pasta [`job-descriptions`](./job-descriptions/):

##### Liderança Executiva
- [Chief Technology Officer (CTO)](./job-descriptions/chief-technology-officer.md)
- [Chief Data Officer (CDO)](./job-descriptions/chief-data-officer.md)
- [Chief Information Security Officer (CISO)](./job-descriptions/chief-information-security-officer.md)
- [VP de Engenharia](./job-descriptions/vp-engenharia.md)
- [VP de Produto](./job-descriptions/vp-produto.md)

##### Liderança Técnica
- [Head de Engenharia](./job-descriptions/head-engenharia.md)
- [Head de Dados & IA](./job-descriptions/head-dados-ia.md)
- [Head de Segurança & Compliance](./job-descriptions/head-seguranca-compliance.md)
- [Head de Produto & Design](./job-descriptions/head-produto-design.md)
- [Head de PMO](./job-descriptions/head-pmo.md)

##### Especialistas e Arquitetos
- [Arquiteto de Solução](./job-descriptions/arquiteto-de-solucao.md)
- [Arquiteto de Dados](./job-descriptions/arquiteto-de-dados.md)
- [Arquiteto de Segurança](./job-descriptions/arquiteto-de-seguranca.md)
- [Arquiteto de Nuvem](./job-descriptions/arquiteto-de-nuvem.md)
- [Product Owner](./job-descriptions/product-owner.md)

##### Time Técnico Operacional
- [Engenheiro(a) de Software](./job-descriptions/engenheiro-software.md)
- [Engenheiro(a) de Dados](./job-descriptions/engenheiro-dados.md)
- [Engenheiro(a) de Infraestrutura](./job-descriptions/engenheiro-infraestrutura.md)
- [Engenheiro(a) de Segurança](./job-descriptions/engenheiro-seguranca.md)
- [Engenheiro(a) de QA (Quality Assurance)](./job-descriptions/engenheiro-qa.md)

### 2. 🗺️ Mapa de Carreira {#mapa-carreira}
A pasta `mapa-de-carreira` contém o mapa de carreira completo, detalhando:
- Pilares organizacionais (Liderança Executiva, Liderança Técnica, Especialistas, Time Operacional)
- Trilhas de carreira por área (Engenharia, Dados, Infraestrutura, Segurança, Produto)
- Critérios de progressão
- Movimentações na carreira (vertical, horizontal, para liderança)
- Modelo de avaliação e desenvolvimento
- Implementação e evolução do mapa

## 🚀 Como Utilizar {#como-utilizar}

<best-practice>
Utilize este repositório como referência para:
</best-practice>
1. Recrutamento e seleção de profissionais
2. Definição de expectativas claras para cada cargo
3. Avaliações de desempenho
4. Planejamento de carreira dos colaboradores
5. Estruturação de equipes técnicas

## 🤝 Contribuição {#contribuicao}

Sugestões e melhorias são bem-vindas! Para contribuir:
1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-descricao`)
3. Commit suas mudanças (`git commit -m 'Adiciona descrição para cargo X'`)
4. Push para a branch (`git push origin feature/nova-descricao`)
5. Abra um Pull Request

## 🎯 Contexto e Objetivo {#contexto-objetivo}

<!-- summary:start -->
> Este mapa de carreira e as descrições de cargos foram desenvolvidos para garantir clareza de resultados, controle de riscos, foco em experiência do usuário, compliance, qualidade de desenvolvimento, arquitetura robusta, automação, gestão de dados e uso inteligente de IA.
<!-- summary:end -->

- **Clareza de resultados**: Definições claras de responsabilidades e métricas de sucesso
- **Controle de riscos e custos**: Papéis com responsabilidades específicas para gestão de riscos
- **Experiência do usuário**: Foco em entregar valor através de UX/UI de qualidade
- **Compliance**: Atenção especial às normas e diretivas aplicáveis ao negócio
- **Qualidade de desenvolvimento**: Aplicação das melhores práticas de engenharia de software
- **System Design**: Arquitetura forte para sistemas distribuídos
- **DevOps e IaC**: Infraestrutura como código e automação
- **Gestão de dados**: Tratamento primoroso de dados
- **Inteligência Artificial**: Uso inteligente de IA para geração de insights e automação

A estrutura proposta equilibra a necessidade de especialização técnica com uma visão integrada de produto, permitindo tanto crescimento vertical quanto horizontal para os profissionais.

## 🧑‍💻 Diferenças entre Níveis de Senioridade {#senioridade}

Para entender as diferenças gerais entre os níveis de senioridade (Júnior, Pleno, Sênior, Especialista) em tecnologia, consulte o arquivo [`senioridade.md`](./senioridade.md). Lá você encontrará uma explicação genérica e aplicável a qualquer área de atuação técnica.

## 📄 Licença {#licenca}

Este material é compartilhado sob a licença MIT. Sinta-se livre para adaptar às necessidades específicas da sua organização.

## Referências {#referencias}

- [MIT License](https://opensource.org/licenses/MIT)