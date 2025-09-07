# Guia Prático: Integração ADF + Azure DevOps

## 1. Criar Projeto no Azure DevOps
- Criar organização e projeto.
- Configurar repositório Git.

## 2. Configurar Branches
- Branch principal: `main`
- Branches de feature: `feature/*`
- Políticas de PR: revisão obrigatória

## 3. Conectar ADF ao Repositório
- No ADF: Manage > Git Configuration
- Tipo: Azure DevOps Git
- Repositório e projeto
- Escolher branch principal

## 4. Versionamento de Artefatos
- Linked Services, Datasets, Pipelines, Triggers
- Commit automático ou manual via ADF

## 5. Automatização com Pipelines
- Configurar CI/CD usando `azure-pipelines.yml`
- Validar e sincronizar artefatos
- Preparar deploy automático para outros ambientes

