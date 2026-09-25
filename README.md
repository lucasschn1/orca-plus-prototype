# Orça+ — Protótipo de Alta Fidelidade

Trabalho da disciplina **Interação Humano-Computador**, do curso de **Análise e Desenvolvimento de Sistemas** da **PUCPR**.

O **Orça+** é uma solução para profissionais autônomos criarem, enviarem e acompanharem orçamentos de forma rápida e profissional. Este repositório contém o protótipo de alta fidelidade das telas do sistema, feito em HTML e CSS.

## Perfis de usuário

O protótipo contempla três perfis:

- **Autônomo** — app mobile usado pelo profissional para criar e acompanhar orçamentos.
- **Cliente** — página que o cliente recebe para visualizar e aprovar o orçamento.
- **Gestor** — painel web para o gestor acompanhar a equipe.

## Telas

| Código | Tela                     | Perfil   | Requisitos atendidos       |
| ------ | ------------------------ | -------- | -------------------------- |
| A1     | Login                    | Autônomo | —                          |
| A2     | Início                   | Autônomo | RF-007                     |
| A3     | Configurações            | Autônomo | RF-002                     |
| A4     | Novo orçamento           | Autônomo | RF-003                     |
| A5     | Resumo do orçamento      | Autônomo | RF-003                     |
| A6     | Orçamento gerado         | Autônomo | RF-004 · RF-005 · RF-006   |
| A7     | Meus orçamentos          | Autônomo | RF-007 · RF-011            |
| A8     | Financeiro               | Autônomo | RF-011 · RF-016            |
| C1     | Orçamento recebido       | Cliente  | RF-005 · RF-008            |
| C2     | Confirmação              | Cliente  | RF-009 · RF-010            |
| G1     | Visão geral da equipe    | Gestor   | RF-012 · RF-013            |
| G2     | Revisar proposta         | Gestor   | RF-013 · RF-014 · RF-015   |
| G3     | Fluxo de caixa           | Gestor   | RF-016                     |

## Estrutura do projeto

```
Orca-prototipo/
├── orca-telas.html   # Todas as telas do protótipo
└── style.css         # Estilos, cores e componentes visuais
```

## Autores

- Lucas Schneider
