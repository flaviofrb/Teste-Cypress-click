# Teste-Cypress-click

Projetos de automação com Cypress desenvolvidos logo quando entrei na área de QA, como parte dos primeiros estudos em automação de testes.

---

## Projetos

### 1. Testes Funcionais — Site El-Shammah Crew

Automação de testes funcionais no site do grupo de dança El-Shammah Crew, cobrindo as principais funcionalidades da página.

**Cenários automatizados:**

- Verificação do banner rotativo (3 slides)
- Navegação pelo menu e validação das seções
- Verificação dos integrantes do grupo no carrossel
- Verificação dos momentos históricos do grupo
- Validação dos links e redes sociais do rodapé
- Verificação dos botões de contato com `target="_blank"`
- Validação das redes sociais de cada integrante
- Validação dos links de cada momento histórico

---

### 2. Prática de Cliques — cy.click()

Pequeno projeto criado para demonstrar e praticar diferentes situações de clique com Cypress, explorando casos que são frequentemente negligenciados no dia a dia.

**Situações cobertas:**

- Clique em botão não visível inicialmente
- Clique em botão que aparece após delay (conteúdo assíncrono)
- Clique em botão desabilitado que é habilitado após delay
- Clique em botão com ícone
- Clique em botão oculto com `visibility: hidden`

---

## Pré-requisitos

- Node.js v18.15.0 ou superior
- npm v9.5.0 ou superior

---

## Instalação

```bash
npm install
```

## Executar os testes

**Modo headless:**
```bash
npm test
```

**Modo interativo:**
```bash
npm run cy:open
```

---

## Sobre

Projetos desenvolvidos no início da minha jornada como QA Engineer, com foco em aprender os fundamentos da automação de testes com Cypress — desde a validação de funcionalidades reais até a compreensão de comportamentos de clique em diferentes situações de UI.

---

## Autor

**Flávio Frank** | QA Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-flavio--frank-blue)](https://www.linkedin.com/in/flavio-frank/)
[![GitHub](https://img.shields.io/badge/GitHub-flaviofrb-black)](https://github.com/flaviofrb)
