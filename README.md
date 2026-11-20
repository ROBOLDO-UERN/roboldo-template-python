# 🐍 [TEMPLATE] Projeto Python — ROBOLDO (LAR / UERN)

Template oficial da organização **[ROBOLDO-UERN](https://github.com/ROBOLDO-UERN)** para criação de novos trabalhos, módulos de IA, visão computacional, controle ou navegação em **Python**.

## 🚀 Como usar este Template
1. Clique no botão verde **"Use this template"** -> **"Create a new repository"** dentro da organização `ROBOLDO-UERN`.
2. Ajuste o arquivo `.github/CODEOWNERS` para incluir o Team da sua **Zona de Projeto** (ex.: `@ROBOLDO-UERN/zona-ia` ou `@ROBOLDO-UERN/zona-slam`).
3. Crie ou vincule a Issue do seu trabalho no **[Painel Geral da Organização (Project #6)](https://github.com/orgs/ROBOLDO-UERN/projects/6)**.

## ⚙️ CI/CD Pré-Configurado
Este template já vem integrado ao workflow reutilizável da organização (`reusable-python-ci.yml`), que executa automaticamente:
- Validação de sintaxe Python (`compileall`)
- Linter de código (`ruff`)
- Testes unitários (`pytest`)
